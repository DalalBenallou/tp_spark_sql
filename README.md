🧠 TP Spark SQL — Analyse des incidents d’une entreprise industrielle
Ce projet vise à démontrer comment exploiter Apache Spark SQL avec Java pour analyser des données liées aux incidents survenus dans une entreprise industrielle. L’application est conçue pour être testée en local, puis facilement déployée sur un cluster Spark via Docker.

📋 Contexte de l'exercice
Objectif : créer une application Spark capable de traiter un fichier CSV nommé incidents.csv, regroupant les incidents déclarés dans différents services de l’entreprise.

L’application devra permettre :

De compter le nombre total d’incidents par service.

D’identifier les deux années au cours desquelles le plus grand nombre d’incidents a été enregistré.

Exemple de contenu du fichier CSV :

python-repl
Copier
Modifier
Id,titre,description,service,date
1,Panne serveur,Serveur crashé,IT,2023-03-15
2,Fuite d'eau,Canalisation percée,Maintenance,2022-06-20
3,Erreur SAP,Transaction échouée,IT,2023-08-09
...
📁 Organisation du projet
css
Copier
Modifier
TP_SparkSQL/
├── src/
│   └── main/java/ServiceIncidents.java
├── incidents.csv
├── pom.xml
⚙️ Technologies utilisées
Java (version 11 ou supérieure)

Apache Spark 3.5.5

Spark SQL

Maven

📸 Résultats attendus
L'application doit produire en sortie :

Le nombre d’incidents enregistrés pour chaque service (IT, Maintenance, etc.)

Les deux années les plus touchées par les incidents

Ces résultats seront affichés directement dans le terminal.

✍️ Réalisé par
Dalal Benallou
Travail pratique de Big Data — Spark SQL
Mai 2025
