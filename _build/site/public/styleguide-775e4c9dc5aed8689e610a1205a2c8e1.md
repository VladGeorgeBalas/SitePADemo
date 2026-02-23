---
title: Style Guide
---

## Headere si sectiuni

Pentru a evita probleme la imbricarea sectiunilor, se folosesc `h2` pentru titlurile principale din pagina. In acelasi timp, titlul paginii se va defini in frontmatter, nu prin markdown, pentru a avea control asupra toc-ului.

Numele sectiunilor trebuie sa fie normal scris, fara adaugari hard-coded precum numere de forma `1)` sau alte stiluri ce pot fura din atentie

:::{code} markdown
:linenos:

---
title: "Titlu"
---

## Prima sectiune
:::

Subsectiunile folosesc header daca sunt destul de importante incat sa se afle in lista continuturilor, caz in care numarul acestora este cu 1 mai mare decat al header-ului parinte. In cazul in care subsectiunea nu este destul de importanta, se va folosi bold pe prima idee a primului paragraf.

:::{code} markdown
:linenos:

## Prima sectiune
### Prima subsectiune

## A doua sectiune
**Asa arata** o alta idee ce merita propriul paragraf.
:::

## Definitii si observatii

Pentru definitii se vor folosi admonitii de tip `note` avand ca titlu notiunea definita. Similar, pentru observatii, se vor folosi admonitii de tip `tip` avand optional un titlu reprezentativ

## Notiuni si emphasis

Cand se doreste scrierea clara a unei denumiri se va folosi sintaxa pentru cod inline, si anume ` \` `