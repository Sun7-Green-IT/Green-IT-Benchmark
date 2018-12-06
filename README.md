# Green-IT-Benchmark

## Contexte 

Définition : Démarche d’amélioration continue qui vise à réduire l’empreinte écologique, économique et sociale des technologies de l’information et de la communication.

Le but du projet est de réaliser un benchmark de plusieurs api REST sur différents langages et différents frameworks

## Candidats

&nbsp;**Express** v4.16.3 -> NodeJS v8.10.0

&nbsp;**Hapi** v17.6.0 -> NodeJS v8.10.0

&nbsp;**Rocket** v0.3.17 -> Rust v1.31.0-nightly

&nbsp;**Laravel** v5.7 -> PHP v7.2.13

## Benchmark

Pour la construction de notre benchmark, nous allons tester nos différentes api avec 4 différentes requêtes sur l’api :

1. Hello World - Une réponse en JSON qui contient en string, un hello world.
2. Simple Listing - Nous avons une base de données Postgres et nous faisons une requête sur une table contenant 1 millions d’users

Nous utilisons wrk pour les tests de benchmark http

`wrk -d1s http://exemple/com`

