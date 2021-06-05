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
- Hasura per la comoditat de generar automàticament la API i el sistema d'autorització
- VueJS per ser una llibreria amb una sèrie de plugins integrats que ens faciliten fer tasques com ara el _routing_.
- Quasar per l'extensa llibreria de components adaptats sobretot a Material Design i per la facilitat d'exportar el nostre projecte no només a web i pwa, sino també a aplicacions Android, iOS i escriptori si fos necessari.
- Firebase Auth perquè fer un sistema d'autenticació ben fet és més complicat del que pot semblar, aleshores sempre és preferible usar un sistema madur com pot ser el de Firebase, amb una fàcil integració amb login social.
- Firebase Functions per la integració que té amb Firebase Auth i Firebase Storage.
