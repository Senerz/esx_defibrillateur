**Défibrillateur**

Un défibrillateur en item et utilisable à l'infini.

__Script requis__ :
- esx_ambulancejob

__Ordre à start dans le "server.cfg"__ : 
- start esx_ambulancejob
- start esx_defibrillateur

__Guide d'installation__ :
- Téléchargé le script.
- Dézippé le script.
- Renommé le dossier du script en "esx_defibrillateur" (enlevé le "-master").
- Start le script dans "server.cfg".
- Dans <esx_ambulancejob/server/main.lua> -> ligne 10 modifié la ligne par :


Ancien :
--if xPlayer.job.name == 'ambulance' then

Nouveau :
--if xPlayer.job.name == 'ambulance' then

if true then 


__Lien de téléchargement du script__ :

https://github.com/Senerz/esx_defibrillateur

__Lien de téléchargement du script d'origine__ :

https://github.com/Senerz/esx_defibrillateur
