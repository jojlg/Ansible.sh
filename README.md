# Création de l'utilisateur ansible :

* Ajoute un nouvel utilisateur ansible avec un mot de passe provisoire.
* Force l'utilisateur à changer son mot de passe lors de sa première connexion.
* Configuration des permissions :
* Ajoute l'utilisateur ansible au groupe sudo
* Change les permissions du répertoire personnel de l'utilisateur ansible.

# Installation d'Ansible (en tant qu'utilisateur ansible) :

* Met à jour la liste des paquets.
* Installe Ansible et l'outil tree (facultatif).

# Configuration SSH :

* Crée le répertoire .ssh dans le répertoire personnel de l'utilisateur ansible.
* Génère une clé SSH de type ed25519 pour l'utilisateur ansible.
* Ajoute la clé publique générée au fichier authorized_keys
