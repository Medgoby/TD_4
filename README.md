# TD4
### 1- Dockerfile: Creation d'un fichier Dockerfile qui contient toutes les instructions rélatives à la création de l'image alpine:1.0.0 depuis la version 3.15.0 de alpine

##### Telecharger l'image de base  de alpine pour notre contenaire
FROM alpine:3.15.0

##### Indiquer à notre contenaire une commande à effectuée

CMD echo hello-alpine, je suis Mohamed et c est mon premier container depuis ma première image alpine

## Construire l'image avec docker build

docker build . -t mohamedbarry9625/hello-alpine:1.0.0

'''-t pour renomer l'image et .(point) pour indiquer que l'on veut construire cette image dans le dossier de reference'''

### Verification
docker run --name bary mohamedbarry9625/hello-alpine:1.0.0