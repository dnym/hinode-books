---
author: Mark Dumay
title: Komponenter
date: 2023-09-23
description: Använd kortkoder för att lägga till fördefinierade komponenter som drivs av externa bibliotek.
tags: ["bootstrap", "kortkoder"]
thumbnail:
  url: img/puzzle.jpg
  author: Ryoji Iwata
  authorURL: https://unsplash.com/@ryoji__iwata
  origin: Unsplash
  originURL: https://unsplash.com/photos/5siQcvSxCP8
modules: ["katex", "leaflet", "lottie"]
---

Hinode tillhandahåller flera kortkoder ovanpå de vanliga [Bootstrap elements]({{< relref "bootstrap-elements" >}}). Se den [officiella dokumentationen](about:blank) för mer information.
Animation

## Animation

Som ett exempel visar följande kortkod en animation som spelas när du svävar.

<!-- markdownlint-disable MD037 -->
{{< example lang="hugo" >}}
{{< /example >}}
<!-- markdownlint-enable MD037 -->

## Formel (KaTeX)

Som ett exempel återger följande markdown två formler som använder KaTeX-typsättningsbiblioteket.

{{< example lang="markdown" >}}
Detta $-b \pm \sqrt{b^2 - 4ac} \over 2a$ är en inline-formel

Detta är inte en inline-formel:

$$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$$  
$$\forall x \in X, \quad \exists y \leq \epsilon$$
{{< /example >}}

## Karta

Som ett exempel visar följande kortkod en interaktiv karta över staden Amsterdam.

<!-- markdownlint-disable MD037 -->
{{< example lang="hugo" >}}
{{</* map lat=52.377 long=4.90 zoom=13 popup="Amsterdams centralstation" popup-lat=52.378062 popup-long=4.900562 */>}}
{{< /example >}}
<!-- markdownlint-enable MD037 -->
