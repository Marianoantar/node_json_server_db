Hice un pequeño servidor que expone un json como base de datos. 
- Primero instale el paquete json-server. (npm install json-server)
- Segundo cree un archivo db.json con la estructura del json.
- Tercero modifique el archivo package.json para agregarle al objeto "scripts" la linea:  "start": "json-server --watch db.json"
- Cuarto use Postman para agregar, modificar, borrar, editar los datos.
- Quinto cree el archivo .gitignore y le agregué la carpeta node_modules/ para que no suba al repositorio git la carpeta con todos los paquetes instanlados
