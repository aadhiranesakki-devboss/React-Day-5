# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

The link https://startbootstrap.com/themes/admin-dashboard is no longer exists so please use this project and setup your code.


Router
1. npm i react-router-dom
2. Import BrowserRouter,Routes, Route from react-router-dom
3. If any of your component need access for routes in your application, then it should be definitely children of BrowserRouter
4. BrowserRouter---> Routes ---> Route(path,element)
5. When the spiecified path is loaded in browser the mapped component will be loaded.
6. Navigate component helps you in redirection to the specified routes
7. Link Component is similar to <a></a> where anchor tag helps navigating external links and Link component helps in navigating Internal Routes