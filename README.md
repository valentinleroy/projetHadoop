# projetHadoop

Ce projet se base sur le repo bde2020. Ce repertoire nous a fourni les ressources docker qui nous permettent de lancer les conteneurs qui composent notre solution avec docker compose.

# Etape 1 : Récuperer sur dockerhub les images nécessaires au fonctionnement de la solution
 - docker pull bde2020/hadoop-resourcemanager   
 - docker pull bde2020/hadoop-historyserver     
 - docker pull bde2020/hadoop-nodemanager       
 - docker pull bde2020/hadoop-datanode          
 - docker pull bde2020/hadoop-namenode          
 - docker pull bde2020/hadoop-datanode          
 - docker pull bde2020/hadoop-resourcemanager   
 - docker pull bde2020/hadoop-base              
 
# Etape 2 : executer le docker-compose pour lancer le cluster
 - docker-compose up
