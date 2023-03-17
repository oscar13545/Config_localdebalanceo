# Config_localdebalanceo
Código para su ejecución 
```
$ ansible-playbook playbook.yml
```
### Playbook-mongo
***
Lo que hace este código es instalar todo lo necesario para usar MongoDB, y luego mediante lineinfile se cambia la línea de bindIp para agregar las IP de las instancias que vana usar mongoDB.

### Playbook-compose 
***
Lo que hace es instalar docker-compose y luego instala git para poder clonar el repositorio de To-do List, luego con docker-compose construye las instancias de Docker fácilmente.
