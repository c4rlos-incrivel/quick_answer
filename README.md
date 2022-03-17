# quick_answer
Elaboracao automatizada de Notas, Oficios, Memorandos Internos, Anuncios, Requerimentos, Convocatorias, etc

# start the containers or 
- docker compose up -d
ou
- docker-compose up -d

# Udpate das dependencias
- docker exec -it answer-php bash
- cd /projects/quick_answer
- composer update

# Portas dos containers (feel free to modify)
- answer-nginx: 8091 or 443
- answer-php: 9000
- answer-mysql: 3306
- answer-node-npm: 9002
- adminer: 8090

# 
