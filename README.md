# API-HackersNews
Work for Webstart to call an API with fetch

Créer une single page application en javascript qui permet d'afficher les top news du site
https://news.ycombinator.com/ et rediriger vers l'url de la news.

Documentation de l'API : https://github.com/HackerNews/API

La page doit au chargement faire une requête qui va récupérer les top articles du site
(https://hacker-news.firebaseio.com/v0/topstories.json) et en afficher les 10 premiers.
Vous devrez afficher les titre des articles dans un lien. Vous devrez aussi afficher l'utilisateur
qui a posté la news et la date et heure du publication. Pour cela, vous devrez faire une
requête sur https://hacker-news.firebaseio.com/v0/item/8863.json où 8863 sera l'id de la
news que vous voudrez récupérer.
Au clic sur un lien, vous devrez rediriger vers l'url de la news.
