---
template: overrides/main.html
---

# To'lovlar

Material for MkDocs goes at great lengths to support the largest possible range
of browsers while retaining the simplemost possibilities for customization via
modern CSS features like [custom properties] and [mask images].

  [custom properties]: https://caniuse.com/css-variables
  [mask images]: https://caniuse.com/mdn-css_properties_mask-image

## To'lovlar miqdori

The following table lists all browsers for which Material for MkDocs offers full
support, so it can be assumed that all features work without degradation. If you
find a feature not to be working in a browser in the supported version range,
please [open an issue]:

<figure markdown>

|        Xizmatlar turlari             | Darajaga mubofiq platforma to'lovi    |
| ------------------------------------ | ------: | ------:  | ------: | 
|                                      |    I    |   II     |  III    |
| :fontawesome-brands-chrome: Chrome   |   49+   |    49+   | 25.65%  |
| :fontawesome-brands-safari: Safari   |     10+ |    49+   |  4.63%  |
| :fontawesome-brands-edge: Edge       |     79+ |    49+   |  3.95%  |
|                                      |         |          |         |
  <figcaption markdown>

Browser support matrix sourced from [caniuse.com].[^1]

  </figcaption>
</figure>

  [^1]:
    The data was collected from [caniuse.com] in January 2022, and is primarily
    based on browser support for [custom properties], [mask images] and the
    [:is pseudo selector] which are not entirely polyfillable. Browsers with a
    cumulated market share of less than 1% were not considered, but might still
    be fully or partially supported.

Note that the usage data is based on global browser market share, so it could
in fact be entirely different for your target demographic. It's a good idea to
check the distribution of browser types and versions among your users.

  [open an issue]: https://github.com/squidfunk/mkdocs-material/issues/new/choose
  [caniuse.com]: https://caniuse.com/
  [:is pseudo selector]: https://caniuse.com/css-matches-pseudo

## Bank hisobi ma'lumotlari

Albeit your site might not look as perfect as when viewed with a modern browser,
the following older browser versions might work with some additional effort:

- :fontawesome-brands-firefox: __Firefox 31-52__ – icons will render as little
  boxes due to missing support for [mask images]. While this cannot be
  polyfilled, it might be mitigated by hiding the icons altogether.
- :fontawesome-brands-edge: __Edge 16-18__ – the spacing of some elements might
  be a little off due to missing support for the [:is pseudo selector], which
  can be mitigated with some additional effort.
- :fontawesome-brands-internet-explorer: __Internet Explorer__ - no support,
  mainly due to missing support for [custom properties]. The last version of
  Material for MkDocs to support Internet Explorer is
  [:octicons-tag-24: 4.6.3][IE support].

  [IE support]: https://github.com/squidfunk/mkdocs-material/releases/tag/4.6.3

## Pul yechish

[Docusaurus] by Facebook is a very popular documentation generator and a good
choice if you or your company are already using [React] to build your site.
It will generate a [single page application] which is fundamentally different
from the site Material for MkDocs generates for you.

__Advantages__

- Very powerful, customizable and extendable
- Provides many components that aid in technical writing
- Large and rich ecosystem, backed by Facebook

__Challenges__

- High learning curve, JavaScript knowledge mandatory
- JavaScript ecosystem is very volatile, rather high maintenance
- More time needed to get up and running

While [Docusaurus] is one of the best choices when it comes to documentation
sites that output a single page applications, there are many more solutions,
including [Docz], [Gatsby], [Vuepress] and [Docsify] that approach
this problem similarily.

  [Docusaurus]: https://docusaurus.io/
  [React]: https://reactjs.org/
  [single page application]: https://en.wikipedia.org/wiki/Single-page_application
  [Docz]: https://www.docz.site/
  [Gatsby]: https://www.gatsbyjs.com/
  [VuePress]: https://vuepress.vuejs.org/
  [Docsify]: https://docsify.js.org/