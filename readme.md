# Prueba el proyecto

https://r4p0so.github.io/Piano/

# Empaquetado web

- Tengo ofuscacion
- Tengo mimificación
- Tengo compresion de imagenes
- Tree shaking
- Tengo preprocesadores css (scss)
- Tengo frameworks de css (tailwind)
- Tengo frameworks web(react, vue)
- uso de lenguajes que no sean javascript(typescript, jsx)
- Tengo mecanismos de optimizacion
- Servidor web de pruebas
- Testing
- etc
  
# Empaquetadores famosos

- webpack(en descenso)
- rollup
- wmr
- esbuilt
- parcel
- snowpack
- * vite
  
# Pasos

## Crear un proyecto node a partir de npm
npm init --yes

## Añadir dependencias (ej) tone
npm install tone

## Añadir empaquetador (ej) parcel
npm install --save-dev parcel

    O

npm install -D parcel

## Construimos  y arrancamos la aplicacion
npx parcel src/index.html

npx parcel build src/index.html

## Comandos personalizados en el json
    "dev": "npx parcel src/index.html",
    "prod": "npx parcel build src/index.html",
    "prod-github": "rd /S docs && npx parcel build src/index.html --public-url ./ --dist-dir docs"

    se ejecutan en la consola con por ejemplo npm run dev
## Añadir imports al js

## Añadimos la libreria react
npm install react react-dom