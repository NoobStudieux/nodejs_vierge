# nodejs_vierge
initialisé avec des modules de base et utiliser typescript



tsc doit être installé par npm (npm & nodejs déjà installés).

Les fichiers typescript doivent être compilé en lançant à la racine du projet :

tsc

(actuellement obligé de transpiler uniquement app.ts sinon erreur : à voir)

puis, lancer avec la commande : 

node ./build/server.js

(il faudra peut être re installé type/node (npm install))



Source : 


https://typescript.developpez.com/actu/101684/Ecrire-une-application-NodeJS-avec-TypeScript-par-Yahiko/


pour rappel , express doit être installé sur npm pour creer un nouveau projet express : 

npm install express-generator -g     // install express genenrator
express --view=jade myapp            // créeara dossier "myapp" initialisé
