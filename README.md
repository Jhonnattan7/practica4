# Práctica 4 - Desarrollo Web II

## Planificador de Gastos

Aplicación web para gestionar presupuestos y controlar gastos personales. Permite definir un presupuesto inicial, registrar gastos por categorías, editarlos, eliminarlos y filtrarlos. Los datos se persisten en localStorage para mantener la información entre sesiones.

### Tecnologías Utilizadas

- **React 18** - Biblioteca para construir interfaces de usuario
- **Vite** - Herramienta de desarrollo rápida
- **Tailwind CSS** - Framework de estilos
- **Context API + useReducer** - Gestión de estado global
- **LocalStorage** - Persistencia de datos

---

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
