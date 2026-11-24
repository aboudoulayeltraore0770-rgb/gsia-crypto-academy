# Bot Telegram (étape facultative)

La première version de l'application fonctionne sans bot. Pour avoir un bot de bienvenue et des commandes, il faut un petit serveur Node.js hébergé séparément (Render, Railway ou VPS).

1. Dans Telegram, contacter `@BotFather`, envoyer `/newbot`, suivre les instructions et copier le token.
2. Créer les variables d'environnement `BOT_TOKEN` et `APP_URL` sur l'hébergeur. Ne jamais les inscrire dans le code public.
3. Utiliser l'API officielle Telegram Bot API en HTTPS.
4. Limiter le bot à des réponses pédagogiques : `/start`, `/cours`, `/securite`, `/app`.
5. Ne jamais demander de phrase de récupération, clé privée, code bancaire ou dépôt crypto.
6. Ajouter une politique de confidentialité avant de collecter des données personnelles.

Le bot n'est pas inclus dans la première version statique, afin de ne pas exposer de secret ni faire croire qu'un bot est déjà opérationnel. Documentation officielle : https://core.telegram.org/bots/api
