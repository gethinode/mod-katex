# Hinode Module - KaTeX

<!-- Tagline -->
<p align="center">
    <b>A Hugo module to add KaTeX formulas to your Hinode site</b>
    <br />
</p>

<!-- Badges -->
<p align="center">
    <a href="https://gohugo.io" alt="Hugo website">
        <img src="https://img.shields.io/badge/generator-hugo-brightgreen">
    </a>
    <a href="https://gethinode.com" alt="Hinode theme">
        <img src="https://img.shields.io/badge/theme-hinode-blue">
    </a>
    <a href="https://github.com/gethinode/mod-katex/commits/main" alt="Last commit">
        <img src="https://img.shields.io/github/last-commit/gethinode/mod-katex.svg">
    </a>
    <a href="https://github.com/gethinode/mod-katex/issues" alt="Issues">
        <img src="https://img.shields.io/github/issues/gethinode/mod-katex.svg">
    </a>
    <a href="https://github.com/gethinode/mod-katex/pulls" alt="Pulls">
        <img src="https://img.shields.io/github/issues-pr-raw/gethinode/mod-katex.svg">
    </a>
    <a href="https://github.com/gethinode/mod-katex/blob/main/LICENSE" alt="License">
        <img src="https://img.shields.io/github/license/gethinode/mod-katex">
    </a>
</p>

## About

![Logo](https://raw.githubusercontent.com/gethinode/hinode/main/static/img/logo.png)

Hinode is a clean blog theme for [Hugo][hugo], an open-source static site generator. Hinode is available as a [template][repository_template], and a [main theme][repository]. This repository maintains a Hugo module to add [KaTeX][katex] to a Hinode site. Visit the Hinode documentation site for [installation instructions][hinode_docs].

## Notes

> [!IMPORTANT]
> Hugo v0.132.0 introduced (experimental) support for [server-side rendering of KaTeX expressions](https://gohugo.io/functions/transform/tomath/).

This modules exposes only one of the extensions by default. All extensions provided by KaTeX are available in the `dist/contrib` folder. Override or modify the mount configuration in `config.toml` as needed.

- [x] `auto-render.js`: Automatically renders all of the math inside text
- [ ] `copy-tex.js`: When selecting and copying KaTeX-rendered elements, copies their LaTeX source to the clipboard
- [ ] `mathtex-script-type.js`: Automatically displays LaTeX math inside script tags with type=math/tex
- [ ] `mhchem.js`: Write beautiful chemical equations easily
- [ ] `render-a11y-string.js`: Add accessible alternative text to KaTeX equations

<!-- MARKDOWN LINKS -->
[hugo]: https://gohugo.io
[hinode_docs]: https://gethinode.com
[katex]: https://katex.org
[katex_extensions]: https://katex.org/docs/libs.html#extensions
[repository]: https://github.com/gethinode/hinode.git
[repository_template]: https://github.com/gethinode/template.git
