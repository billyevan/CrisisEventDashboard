# Projet de fouille de graphe

**Description du projet**
Ce projet vise à explorer et à analyser un graphe social construit à partir de tweets liés à des événements de crise. 
Le graphe contient des informations sur les utilisateurs, les tweets, les retweets, les réponses et les mentions. 
L'objectif principal est d'extraire des informations pertinentes sur l'activité sociale pendant les événements de crise 
et d'identifier les utilisateurs influents.

Pour la partie dashboard, nous avons effectué une analyse exploratoire des données en premier temps sur le notebook 'Graph analysis'.
Ensuite, nous avons extrait les fonctions et scripts nécessaires pour la création du dashboard sur le fichier 'app.py' et 'utils.py'
dans le dossier 'Dashboard'.
Il se peut que le notebook ne contienne pas toutes les fonctions nécessaires pour le dashboard,
mais toutes les fonctions nécessaires pour le dashboard sont dans le fichier 'utils.py' ou dans le fichier 'app.py'.

**Exécution du projet**

@Requirements
1. Assurez-vous que les bibliothèques nécessaires sont installées. la liste 
!pip install networkx==3.1 
!pip pandas==2.0.3 
!pip plotly==5.15.0 
!pip matplotlib==3.7.2 
i!pip python==8.14.0 collections==0.0.0 
!pip  numpy==1.25.2
!pip install streamlit==1.25.0

Pour executer la partie sur les dashbord, il faut:
1. S'assurer que les bibliothèques nécessaires sont installées, notamment Streamlit.
2. Exécuter la commande `streamlit run Dashboard/app.py`.
3. Une nouvelle fenêtre s'ouvrira dans votre navigateur par défaut. Vous pourrez alors interagir avec le tableau de bord.

Pour la partie embedding il faut:
#   C r i s i s E v e n t D a s h b o a r d  
 