---
author: Mark Dumay
title: Components
date: 2023-09-23
description: Use shortcodes to add predefined components powered by external libraries.
lead: "In the ever-evolving landscape of web development, maintaining a streamlined and efficient workflow is crucial. Hugo, a popular static site generator, offers a powerful feature to enhance your site's functionality: shortcodes. These predefined snippets of code allow you to effortlessly integrate complex components into your website. By leveraging external libraries, Hugo shortcodes can transform your static site into a dynamic and engaging platform, providing an enhanced user experience without the need for extensive coding. In this post, we'll explore how to utilize Hugo shortcodes to add robust components powered by external libraries, streamlining your development process and elevating your site's capabilities."
tags: ["bootstrap", "shortcode"]
thumbnail:
  url: img/puzzle.jpg
  author: Ryoji Iwata
  authorURL: https://unsplash.com/@ryoji__iwata
  origin: Unsplash
  originURL: https://unsplash.com/photos/5siQcvSxCP8
modules: ["katex", "leaflet", "lottie"]
---
Hinode provides several shortcodes on top of the common [Bootstrap elements]({{< relref "bootstrap-elements" >}}). Refer to the [official documentation](about:blank) for more details.

## Animation

As an example, the following shortcode shows an animation that plays on hover.

<!-- markdownlint-disable MD037 -->
{{< example lang="hugo" >}}
{{< /example >}}
<!-- markdownlint-enable MD037 -->

## Formula (KaTeX)

As an example, the following markdown renders two formulas using the KaTeX typesetting library.

{{< example lang="markdown" >}}
This is an inline $-b \pm \sqrt{b^2 - 4ac} \over 2a$ formula

This is not an inline formula:

$$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$$  
$$\forall x \in X, \quad \exists y \leq \epsilon$$
{{< /example >}}

## Map

As an example, the following shortcode displays an interactive map of the city of Amsterdam.

<!-- markdownlint-disable MD037 -->
{{< example lang="hugo" >}}
{{</* map lat=52.377 long=4.90 zoom=13 popup="Amsterdam Central Station" popup-lat=52.378062 popup-long=4.900562 */>}}
{{< /example >}}
<!-- markdownlint-enable MD037 -->
