### Présentation

Application web full-stack développée avec **Python Flask**, implémentant un système d'authentification multi-rôles sécurisé. Projet réalisé dans le cadre du baccalauréat en informatique à l'UQAC.

### Fonctionnalités

- **Authentification sécurisée** — Mots de passe hachés avec `bcrypt` (sel + hash, jamais stockés en clair)
- **Contrôle d'accès par rôles (RBAC)** — Trois rôles : `admin`, `client 1`, `client 2`, chacun avec son tableau de bord dédié
- **Protection contre le bruteforce** — Verrouillage du compte après 3 tentatives échouées (5 min de blocage, 30 sec entre essais)
- **Validation des entrées** — Validation regex côté serveur pour prévenir les injections
- **Panneau d'administration** — Gestion des utilisateurs, attribution des rôles, réinitialisation des mots de passe, déblocage des comptes
- **Base de données SQLite** — Suivi persistant des utilisateurs et des tentatives de connexion

### Technologies utilisées

| Couche     | Technologie              |
|------------|--------------------------|
| Backend    | Python 3, Flask          |
| Base de données | SQLite 3            |
| Sécurité   | bcrypt, validation regex |
| Frontend   | HTML5, CSS3, Jinja2      |

### Lancement du projet

```bash
git clone https://github.com/mano/Systeme_authentification_web_securise
.git
pip install -r requirements.txt4k
python app.py

---

*Réalisé par : ILBOUDO Soutongnoma Hermann Rodrigue — UQAC*

