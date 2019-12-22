# windows-automatic-bash-script
ejemplo de comandos para correr procesos de instalación con npm desde consola windows

• Bash script automátizado para el sistema operativo windows:
pushd C:\ && git clone https://github.com/null-point-sys/express-apollo-graphql-starter.git && cd express-apollo-graphql-starter && git clone https://github.com/null-point-sys/express-apollo-graphql-starter2.git && npm install && cd express-apollo-graphql-starter2 && move server.js C:\express-apollo-graphql-starter && cd C:\express-apollo-graphql-starter && rmdir /s /Q C:\express-apollo-graphql-starter\express-apollo-graphql-starter2 && npm run server

• Como poner a correr este bash script automátizado en mi equipo:
Abre una consola de windows y pega todo el script anterior y dale enter.

• Explicación del flujo de este bash script automátizado para el sistema operativo windows:
Una vez git clona este primer repositorio https://github.com/null-point-sys/express-apollo-graphql-starter.git en la ruta C:\express-apollo-graphql-starter el bash script ingresa a esta carpeta y clona seguidamente el repositorio https://github.com/null-point-sys/express-apollo-graphql-starter2.git que contiene solo un archivo el server.js apollo express del proyecto y a continuación npm instala las dependencias desde package.json e instala en paralelo node js (node_modules), al finalizar se inicializa el proyecto con npm run server: el BACK graphiql queda corriendo en el navegador en http://localhost:4444/graphiql
