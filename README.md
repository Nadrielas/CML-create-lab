# CML-create-lab

### Doc installation librairie CML :

1 : Créer d'abord un venv. 

2 : https://developer.cisco.com/docs/virl2-client/


### Doc utilisation librairie CML : 

https://pubhub.devnetcloud.com/media/virl2-client/docs/latest/examples.html#creating-a-lab-with-nodes-and-links


### Objectif : 

Créer un script permettant de créer un lab spécifique en fonction d'un choix numéroté au lancement du script. 
A l'execution, les choix seront les suivants : 

Que voulez vous tester via le nouveau lab ? 

1 : Test spanning-tree simple (3 switchs connectés entre eux),

2 : Test routage inter VLAN ROAS simple (un routeur, un switch et deux clients),

3 : Test routage dynamique (3 routeurs, deux switchs et deux clients).