# Bot_meteo_reservation

1- Cloner le repository avec la commande : `git clone https://github.com/Lucile16/Bot.git`

2- Dans une invite de commande, placez vous dans le dossier /Bot que vous venez de cloner

3- Exécuter la commande suivante pour vérifier que vous avez la dernière version de la librairie pip3 : `pip3 install -U pip`

4- Créer un environnement avec la commande : `python3 -m venv ./venv`

5- Activer l'environnement avec la commande : `.\venv\Scripts\activate`

6- Installer rasa avec la commande : `pip3 install rasa`

7- Initialiser rasa avec la commande : `rasa init`

8- Pour que votre bot apprenne le nouveau modèle, lancez la commmande : `rasa train`

9- Pour lancer la conversation avec le bot, lancez la commande : `rasa shell`

**Enfin, suivez ce qui est indiqué dans les fichiers stories.yml et nlu.yml pour tester la météo et la réservation d'un hôtel.**