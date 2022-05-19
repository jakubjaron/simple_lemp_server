# simple_lemp_stack

Projekt zawiera plik docker-compose w którym tworzony jest prosty LEMP stack.

W folderze kod znajduje się plik index.php który wyświetla stronę startową php.

W pliku site.conf jest konfiguracja serwera nginx która pozwala wyświetlić stronę startową index.php


# Klaset swarm

W pliku docker-stack.yml znajduje się zmodyfikowany plik docker-compose na bazie którego uruchamiana jest usługa servera lemp.

polecenie uruchamiające usługę.

```sh
sudo docker stack deploy -c docker-stack.yml lab10_swarm

```
