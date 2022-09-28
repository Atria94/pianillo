# Empaquetado web

- Tengo ofuscacion
- Tengo minificacion
- Tengo compresion de imagenes
- Tree Shaking
- Tengo preprocesadores de css (scss)
- Tengo frameworks de css (tailwind)
- Tengo frameworks web (react, vue)
- Uso de lenguajes que no sean javascript (typescript, jsx)
- Tengo mecanismos de optimizacion del codigo
- Servidor web de pruebas
- Testing
- etc, etc

# Empaquetadores famosos

- webpack
- rollup
- wmr
- esbuilt
- parcel
- snowpack
- **vite**

## Crear un proyecto npm

npm init --yes

## Añadir la dependencia con tonejs (Dependencia de produccion)

npm install tone

## Añadir el empaquetador parcel (Dependencia de desarrollo)

npm install --save-dev parcel

## Construimos y arrancamos la aplicacion

npx parcel src/index.html

## Añadimos la libreria react

npm install react react-dom