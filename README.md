# Curriculum Vitae Matteo Franci

[![Tenere un changelog v1.1.0 badge](https://img.shields.io/badge/changelog-Tenere%20un%20Changelog%20v1.1.0-%23E05735)](CHANGELOG.md)

Curriculum Vitae con approccio docs as code, basato su AsciiDoc

## Requisiti

[![Node JS](https://img.shields.io/badge/Node%20JS-20+-1AC736?style=for-the-badge&logo=node.js&logoColor=white)](https://universe.fugerit.org/src/docs/versions/node.html)

## Quickstart

Versione online  : <https://cv.fugerit.org/cv-franci-matteo.pdf>

Build locale : 

```shell
npm install
```

```shell
./node_modules/asciidoctor-pdf/bin/asciidoctor-web-pdf cv.adoc --template-require ./template.js -o cv.pdf
```

## Risorse

Questo progetto è basato su  :

* [AsciiDoc](https://asciidoc.org/)
* [Asciidoctor](https://asciidoctor.org/)
* [asciidoctor-web-pdf](https://github.com/ggrossetie/asciidoctor-web-pdf)
* <https://flakm.com/posts/cv_asciidoc/>
