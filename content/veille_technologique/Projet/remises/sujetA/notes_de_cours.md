+++
title = "Le language GO"
weight = 2
+++

Ici, on va voir l’utilisation du langage Go pour nous aider à développer des applications efficaces et concurrentes, ce qui n’est qu’un sous-ensemble de tout ce que permet de faire Go dans le monde du développement logiciel.

## c’est quoi Go et pourquoi il existe ?

Go est un langage de programmation compilé, performant et orienté concurrence, qui s’inspire de la simplicité de Pascal et de l’efficacité de C. Il a été créé chez Google par Robert Griesemer, Rob Pike et Ken Thompson, trois ingénieurs reconnus pour leurs travaux sur les systèmes d’exploitation, les compilateurs et le développement de systèmes distribués. Leur objectif était de concevoir un langage moderne, facile à apprendre et capable de gérer efficacement les charges de travail massivement parallèles.
![alt text](/images/Google.webp)

Go a été créé pour rendre la programmation plus rapide, plus simple et plus efficace, surtout dans les projets de grande envergure. Sa syntaxe minimaliste et ses outils intégrés permettent d’écrire facilement aussi bien des petits programmes ou des scripts que des applications complexes, des services web et des systèmes haute performance.

![alt text](/images/GoLogo.png)

## Un langage simple mais puissant

![alt text](/images/simple.png)

L’une des grandes forces de Go est sa simplicité. Contrairement à d’autres langages qui possèdent des dizaines de concepts avancés, Go privilégie une approche minimaliste. Il ne propose pas d’héritage complexe, pas de génériques pendant longtemps (introduits seulement en 2022), et limite volontairement les fonctionnalités pouvant rendre un code difficile à comprendre. Cette philosophie se traduit par un code clair, lisible et facile à maintenir, ce qui fait de Go un excellent choix pour les équipes qui recherchent une grande productivité. Malgré cette simplicité, Go reste extrêmement puissant grâce à la qualité de ses bibliothèques standard et à son écosystème en constante croissance.

## La concurrence : le cœur de Go

La gestion de la concurrence est probablement l’aspect le plus innovant et distinctif de Go. Alors que les threads traditionnels peuvent être lourds et difficiles à synchroniser, les goroutines de Go sont très légères et permettent de lancer des milliers de tâches concurrentes en quelques lignes de code. Leur fonctionnement repose sur un modèle appelé CSP (Communicating Sequential Processes), qui encourage la communication sécurisée entre goroutines via des canaux. Grâce à cela, il devient beaucoup plus facile de programmer des serveurs web, des systèmes d’analyse en temps réel ou des microservices capables de traiter simultanément de nombreuses requêtes sans sacrifier les performances.

## Compagnie utilisant GO
![alt text](/images/GoCampagnie.png)

## Un langage taillé pour le cloud, DevOps et les microservices

![alt text](/images/DevOps.webp)

Au fil du temps, Go a été largement adopté par les entreprises travaillant dans le cloud et les infrastructures modernes. Des outils majeurs comme Docker, Kubernetes, Terraform, Prometheus et Etcd sont tous écrits en Go, ce qui montre à quel point ce langage est adapté aux environnements critiques nécessitant robustesse et efficacité. Sa capacité à produire des exécutables statiques, son faible coût en ressources et sa vitesse d’exécution en font un candidat idéal pour créer des microservices, des outils de déploiement ou des systèmes distribués. Pour un étudiant ou un développeur qui souhaite travailler dans les domaines du backend ou du DevOps, Go représente un atout extrêmement précieux.

## Un écosystème professionnel et un outillage intégré

Contrairement à de nombreux langages qui nécessitent l’installation de frameworks ou d’outils externes, Go propose dès son installation tout le nécessaire pour développer proprement. Les commandes comme go fmt, go build, go run ou go test font partie de la boîte à outils du langage et encouragent de bonnes pratiques. Le formateur automatique gofmt, par exemple, garantit un style uniforme dans tous les projets, ce qui améliore la lisibilité et évite les débats inutiles sur la mise en forme du code. Cet outillage intégré simplifie énormément la vie des développeurs et contribue à la réputation de Go comme un langage “prêt à utiliser”.

## Installation sur Linux

Il existe plusieurs façons d’installer Go sur une distribution Linux. On peut utiliser les dépôts officiels (apt install golang), mais la méthode recommandée par l’équipe Go est d’installer la version officielle disponible sur le site de Go. Dans cette section, nous allons voir la méthode la plus simple à mettre en place, compatible avec Ubuntu/Debian et la majorité des distributions Linux.

``` bash
$ sudo apt update
$ sudo apt install golang -y
$ go version
```