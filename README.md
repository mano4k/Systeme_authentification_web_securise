Développement d'une application web full-stack intégrant un système d'authentification multi-rôles avec les bonnes pratiques de sécurité :


Hachage des mots de passe avec bcrypt (sel aléatoire, jamais stockés en clair)
Contrôle d'accès par rôles (RBAC) : admin, client 1, client 2 — chacun avec un tableau de bord dédié
Protection anti-bruteforce : verrouillage automatique après 3 tentatives échouées, délai de réessai configurable
Validation des entrées côté serveur (regex), gestion de sessions Flask, base de données SQLite


Stack : Python 3, Flask, SQLite, bcrypt, HTML/CSS, Jinja2
