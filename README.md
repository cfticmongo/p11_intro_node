# Instalación de node js en local

Descargar asistente desde [node](https://nodejs.org/es/)

Comprobamos con:

```
node -v
```

```
npm -v
```

# Uso de npm (node package manager) [npm](https://www.npmjs.com/)

## Uso de npm como cli de node

Inicio de proyecto node (desde la carpeta raiz de nuestro proyecto)

```
npm init // -y con esta opción contesta a todo que si
```

## Uso de npm para instalar paquetes

Por ejemplo paquetes con herramientas o funcionalidades de desarrollo

```
npm install <nombre-paquete> --save-dev // Guardar en package json la referencia del paquete como desarrollo
```

Por ejemplo instalamos nodemosn

```
npm install nodemon --save-dev
```

## Uso de npm para reinstalar paquetes

```
npm install // Leer el package json e instalar los paquetes en la versión especificada
```


