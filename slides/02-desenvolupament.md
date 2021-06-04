# Desenvolupament

## Disseny

![](./img/login-menu.svg)

notes:

- Material Design: és un sistema de disseny creat per Google, que ajuda a crear una experiència de usuari diguem-ne més estàndard i reconeixible.

- En l'elaboració del disseny era important incidir en que fos adaptatiu però sobre tot que funcionés bé en mòbils. És el que coneixem com a _Mobile First Design_.

--

![](./img/usuaris.svg)

--

![](./img/serveis.svg)

--

![](./img/blog.svg)

---

# Desenvolupament

## Arquitectura

![](./img/arquitectura_app.svg)

notes:

- 3 parts:
  - VPS per a Hasura
  - Frontend Quasar (VueJS) allotjat a Firebase Hosting
  - Firebase (Functions, Storage, Auth)

- GraphQL per la facilitat de modelar les peticions i les respostes i treballar amb dades relacionades. Descart de Base de dades basada en objectes (NoSQL) com FireStore.
