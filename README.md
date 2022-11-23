# TD4
## 1- Dockerfile: Creation d'un fichier Dockerfile qui contient toutes les instructions rélatives à la création de l'image 

Creation d'une image alpine
version 3.14

##### Telecharger une image de base  pour notre contenaire
FROM alpine :3.14

##### Indiquer à notre contenaire une commande à effectuée

CMD ["echo","Hello world !"]

## **Step 1 :** Construire l'image avec docker build

docker build -t mon_image .

#-t pour renomer l'image (l'appeler mon_image) et .(point) pour indiquer que l'on veut construire cette image dans le dossier de reference