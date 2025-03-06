# Curriculum Vitae Matteo Franci

[![Curriculum Vitae](https://img.shields.io/badge/Curriculum%20Vitae-LATEST-EE3020?labelColor=303030&style=flat&logo=adobe)](https://cv.fugerit.org/cv-franci-matteo.pdf)
[![Tenere un changelog v1.1.0 badge](https://img.shields.io/badge/changelog-Tenere%20un%20Changelog%20v1.1.0-%23E05735)](CHANGELOG.md)

Curriculum Vitae con approccio docs as code, basato su AsciiDoc

## Requisiti

[![Node JS](https://img.shields.io/badge/Node%20JS-20+-1AC736?style=for-the-badge&logo=node.js&logoColor=white)](https://universe.fugerit.org/src/docs/versions/node.html)

## Quickstart

Build locale : 

```shell
npm install
```

```shell
./node_modules/asciidoctor-pdf/bin/asciidoctor-web-pdf cv.adoc --template-require ./template.js -o cv.pdf
```

## CI : Pipeline di build e pubblicazione

Tramite un semplice [workflow GitHub](.github/workflows/gh_pages.yml) viene creato l'artefatto del CV che poi viene pubblicato sulle le GitHub pages : 

<https://cv.fugerit.org/cv-franci-matteo.pdf>

## Risorse

Questo progetto è basato su  :

* [AsciiDoc](https://asciidoc.org/)
* [Asciidoctor](https://asciidoctor.org/)
* [asciidoctor-web-pdf](https://github.com/ggrossetie/asciidoctor-web-pdf)
* <https://flakm.com/posts/cv_asciidoc/>

## Convenzioni

Per i commit viene usata la specifica [Conventional Commits](https://www.conventionalcommits.org/)