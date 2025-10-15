# Desafío Técnico — Desarrollador Frontend Senior (React / Next.js / TypeScript)

### Introducción

Este desafío tiene como objetivo evaluar tus habilidades técnicas en Next.js, React, TypeScript, CSS moderno y tu capacidad para transformar un diseño en una interfaz funcional, escalable y de alta calidad.

Deberás replicar fielmente las 4 pantallas provistas en Figma:
	1.	Auth – Sign in
	2.	Project Overview
	3.	Pricing
	4.	Auth – 404

El objetivo es construir una pequeña aplicación frontend con autenticación mockeada, navegación entre rutas y una estructura de componentes limpia y reutilizable.


### Objetivos principales
	•	Reproducir el diseño del Figma con precisión.
	•	Usar Next.js 14+ con TypeScript.
	•	Aplicar buenas prácticas de componentización, organización de carpetas y clean code.
	•	Implementar autenticación simulada (mock login).
	•	Navegar entre las páginas (Auth → Overview → Pricing → 404).
	•	Asegurar responsividad y consistencia visual.
	•	Incluir tests automatizados para validar componentes clave.


### Stack técnica requerida
	•	Next.js (versión 14 o superior)
	•	React.js
	•	TypeScript
	•	TailwindCSS o Styled Components (elige una)
	•	React Hook Form o Formik (para formularios)
	•	Zod o Yup (para validación)
	•	Mock Service / Context API / Zustand (para manejar la sesión simulada)
	•	ESLint + Prettier configurados
	•	Testing con Jest + React Testing Library (obligatorio)


### Autenticación mockeada

No es necesario implementar un backend real.
Puedes usar un estado global o contexto para simular el login/logout:
	•	Al iniciar sesión en /auth/signin, redirige a /project.
	•	Si el usuario no está autenticado, redirige a /auth/signin.
	•	El botón “Logout” debe cerrar la sesión y redirigir al login.


### Requisitos de Testing

Se deben incluir tests automatizados:
	•	Tests unitarios para componentes principales.
	•	Tests de integración básicos (por ejemplo: login → redirección → logout).
	•	Se recomienda usar Jest + React Testing Library o Vitest + Testing Library.
	•	Ejecutar con el comando:

    npm run test


### Páginas requeridas

1. /auth/signin
	•	Formulario con email y contraseña.
	•	Botón “Sign in” y “Sign in with Google” (no funcional).
	•	Validaciones básicas.
	•	Diseño igual al Figma.

2. /project
	•	Dashboard con cards, gráficos y listas (mock data).
	•	Implementar componentes reutilizables.
	•	Cuidar tipografía, espaciado y consistencia visual.

3. /pricing
	•	Tres planes (Startup, Business, Enterprise).
	•	Layout responsive.
	•	Cada card con precios y características.

4. /auth/404
	•	Página simple con el estado 404.
	•	Botón para volver al home.


### Evaluación

Serás evaluado en los siguientes aspectos:

### Criterio	Descripción
- Fidelidad visual	El diseño coincide con el Figma
- Arquitectura	Organización clara y escalable
- TypeScript	Tipado correcto y limpio
- Lógica	Manejo de estado y autenticación simulada
- Tests	Existencia y calidad de pruebas automatizadas
- Responsividad	Se adapta correctamente a diferentes tamaños
- Código limpio	Buenas prácticas, ESLint, Prettier, nombres claros
- Performance	Uso adecuado de renderizado y optimización



### Entrega
	1.	Crea un repositorio público en GitHub con el nombre lianzo-frontend-challenge.
	2.	Incluye un README.md con tus comentarios o decisiones técnicas.
	3.	Asegúrate de incluir scripts para ejecutar el proyecto y los tests.
	4.	Envía el enlace de tu repositorio (y la demo si la publicas en Vercel) al correo: kalebeoliveira.dev@gmail.com


### Ejecución local

#### Instalar dependencias
- npm install

#### Ejecutar en modo desarrollo
- npm run dev

#### Ejecutar tests
- npm run test

La app estará disponible en http://localhost:3000


### Recursos

Figma: [Link figma](https://www.figma.com/design/z7BEqnLA2Xt0qTGp1VXwGT/Sem-t%C3%ADtulo?node-id=0-1&t=Au4uXA3gLcszcxVb-1)


### Contacto

Si tienes dudas, puedes contactar al equipo técnico de Lianzo a través del correo:
kalebeoliveira.dev@gmail.com


¡Buena suerte y demuestra tu mejor código! 💪
