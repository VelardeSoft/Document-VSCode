# deployVueAngularInNetlify

----------------------------------------------------
- Este comando en para subir proyectos de Frontend desarrollado en Angular19, deploy manualmente hacia Netlify
ng build --configuration=production

Al ejecutar dicho comando se creará una carpeta dist, dentro de ello hay otra carpeta browser, ingresar a dicho carpeta y crear el siguiente archivo: 

_redirects  (dentro de browser)

/*    /index.html   200

- Finalmente, arrastra ese archivo browser
----------------------------------------------------
- Este comando es para hacer el deploy manualmente a Netlify, un proyecto desarrollado en VUE
npm run build    // es importante para que las rutas del Vue Router funcionen en producción.
se creará el archivo dist y dentro de ello crea el archivo : _redirects

/*    /index.html   200

- Finalemente Arrastra dist(Todo lo que esta dentro de dist) a Netlify