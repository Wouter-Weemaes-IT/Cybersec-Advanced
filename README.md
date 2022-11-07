# keycloak-security-example

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs) [![Main Branch workflow](https://github.com/wkrzywiec/keycloak-security-example/actions/workflows/main.yaml/badge.svg?branch=main)](https://github.com/wkrzywiec/keycloak-security-example/actions/workflows/main.yaml)


# Hoe opstarten 

De applicatie opstarten kan als volgt: 
```
docker-compose up -d frontend
```
Het is ook nodig om in uw hosts file deze lijn er mee in te zetten:
```
127.0.0.1 keycloak
```
En tot slot is het nodig de json server te runnen die mee in de website steekt. anders is het niet mogelijk items to te voegen aan het bord of te verwijderen. 

