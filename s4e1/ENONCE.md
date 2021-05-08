
# S4E1 : Installer le service nextcloud

## Installer MariaDB

On veut installer MariaDb sur le groupe `role_db` (qui inclue server1)

* Utiliser le role https://galaxy.ansible.com/adfinis-sygroup/mariadb


## Installer NextCloud

On veut installer Nextcloud sur le groupe `role_app` (qui inclue server0)

* Quel role faut il utiliser ? 
* Choisissez un role existant, testez-le et configurez-le
* Connectez nextcloud à la base de donnée mariadb qui est installée sur server1
* Ecrire le playbook qui correspond

