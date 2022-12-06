## A propos


La forme la plus courante d'authentification est la combinaison d'un nom d'utilisateur et d'un mot de passe ou d'une phrase de passe. Si les deux correspondent à des valeurs stockées dans une table stockée localement, l'utilisateur est authentifié pour une connexion. La force du mot de passe est une mesure de la difficulté à deviner ou à casser le mot de passe par des techniques cryptographiques ou des tests automatisés de valeurs alternatives basés sur des bibliothèques.

Un mot de passe faible peut être très court ou n'utiliser que des caractères alphanumériques, ce qui facilite le décryptage. Un mot de passe faible peut également être facilement deviné par quelqu'un qui établit le profil de l'utilisateur, comme un anniversaire, un surnom, une adresse, le nom d'un animal domestique ou d'un parent, ou un mot courant comme Dieu, amour, argent ou mot de passe.

C'est la raison pour laquelle le CUPP est né, et il peut être utilisé dans des situations telles que les tests de pénétration ou les enquêtes criminelles.

Besoins
------------

Vous avez besoin de Python 3 pour exécuter CUPP.

Démarrage rapide
-----------

    $ python3 cupp.py -h

## Options

  Utilisation : cupp.py [OPTIONS]

                -h      Ce menu

                -i      Questions interactives pour le profilage des mots de passe des utilisateurs

                -w      Utilisez cette option pour profiler un dictionnaire existant,
                ou la sortie WyD.pl pour faire de la pwnsauce :)

                -l      Télécharger de grandes listes de mots à partir du référentiel

                -a      Analyse des noms d'utilisateur et des mots de passe par défaut directement à partir de la base de données Alecto.
                Le projet Alecto utilise des bases de données purifiées de Phenoelit et CIRT qui ont été fusionnées et améliorées.

                -v      Version du programme


## Configuration

   CUPP has configuration file cupp.cfg with instructions.

## Exemple

![cupp-example](![cupp-example]Screenshot/cupp-example.gif)

## License

  This program is free software; you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation; either version 3 of the License, or
  any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this program; if not, write to the Free Software
  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

  See './LICENSE' for more information.

## Original author

  Ce projet a été importé depuis https://github.com/Mebus/cupp by Mebus from:  
  http://www.remote-exploit.org/content/cupp-3.0.tar.gz  
  http://www.remote-exploit.org/articles/misc_research__amp_code/index.html  
  encourager la poursuite du développement de l'outil.
