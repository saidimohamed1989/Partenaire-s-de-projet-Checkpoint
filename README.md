Cahier des charges - Gestion des absences
1. Contexte et problématique
La gestion manuelle des absences entraîne des pertes d'information et un manque de suivi. Ce projet vise à digitaliser ce processus.
2. Objectifs du projet
Développer une application web MERN pour gérer les absences des stagiaires avec validation administrative.
3. Périmètre du projet
Inclus : gestion utilisateurs, absences, justificatifs, statistiques.
Exclus : application mobile, paiements, SMS.
4. Acteurs
Stagiaire : déclare ses absences.
Administrateur : valide et gère.
5. Besoins fonctionnels
- Authentification
- Ajout et validation des absences
- Upload justificatifs
- Dashboard admin
6. Besoins non fonctionnels
Sécurité, performance, ergonomie, compatibilité navigateurs.
7. Architecture technique
Frontend : React
Backend : Node.js / Express
DB : MongoDB
8. Planning
Analyse : 2 jours
Développement : 10 jours
Tests : 2 jours
Déploiement : 1 jour
9. Livrables
Code source, application déployée, documentation.
Stack technique
•	Frontend : React + Redux Toolkit + Bootstrap / MUI
•	Backend : Node.js + Express
•	Base de données : MongoDB (Mongoose)
•	Auth : JWT
•	Upload fichiers : Multer
•	Déploiement :
o	Front → Vercel
o	Back → Render / Railway
o	DB → MongoDB Atlas
Rôles utilisateurs
🧑‍🎓 Stagiaire
•	Se connecter
•	Ajouter une absence
•	Upload justificatif (PDF / image)
•	Consulter ses absences
•	Voir le statut (En attente / Acceptée / Refusée)
👨💼 Admin
•	Voir toutes les absences
•	Valider / refuser
•	Ajouter des stagiaires
•	Voir statistiques (dashboard)
Fonctionnalités principales
✅ Authentification JWT
✅ CRUD absences
✅ Upload justificatifs
✅ Gestion des rôles
✅ Dashboard statistiques
✅ Recherche & filtres
✅ Sécurité middleware



Structure du projet
gestion-absences/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── services/
│   │   └── App.jsx
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   └── server.js

