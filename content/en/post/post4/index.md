---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Lightweight markup languages"
subtitle: "github"
summary: ""
authors: [Varvara Kabanova]
tags: []
categories: []
date: 2022-05-05T17:20:53+03:00
lastmod: 2022-05-05T17:20:53+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

**Markup language with simple unobtrusive syntax**

A Lightweight Markup Language (LML), also called Plain Markup Language or Humane Markup Language, is a markup language with a simple, unobtrusive syntax. It is designed to be easy to write using any generic and easy to read in raw form. Lightweight markup languages ​​are used in applications where the raw document may need to be read as well as the final rendered output.

For example, a person downloading a software library may prefer to read the documentation in a text editor rather than in a web browser. Another application for such languages ​​is to provide data entry in web publications, such as weblogs and wikis, where the input interface is a simple text field. The server software then converts the input into a common document markup language such as HTML.

**Story**

Lightweight markup languages ​​were originally used on text displays that could not display italic or bold characters, so informal methods had to be developed to communicate this information. This formatting choice has naturally been applied to plain text emails. Console browsers may also use similar rendering conventions.

In 1986, the international standard SGML provided a means to define and parse lightweight markup languages ​​using grammars and tag implication. 1998 W3C XML is an SGML profile that does not have these features. However, the SGML Document Type Definition (DTD) for any of the languages ​​listed below is not known.

**Types**

Lightweight markup languages ​​can be categorized by their tag types. Similar to HTML (bold), some languages ​​use named elements that have a common format for start and end tags (e.g. BBCode[b] bold [ / b] ), while proper simplified markup languages ​​are limited to ASCII-only punctuation and others non-letter characters for tags, but some also mix both styles (eg Textile bq. ) or allow inline HTML (eg Markdown ), perhaps extended with custom elements (eg MediaWiki source ).

Most languages ​​distinguish between markup for lines or blocks and shorter sections of text, but some only support inline markup.

Some markup languages ​​are designed for a specific purpose, such as documenting computer code (e.g. POD, RD) or converting to a specific output format (usually HTML) and nothing else, others more generally in an application. This includes whether they are oriented towards text representation or data serialization.

Presentation-oriented languages ​​include AsciiDoc, atx, BBCode, Creole, Crossmark, Epytext, Haml, JsonML, MakeDoc, Markdown, Org-mode, POD, reST, RD, Setext, SiSU, SPIP, Xupl, Texy! , Textile , txt2tags , UDO and Wikitext .

Data serialization-oriented languages ​​include Curl (homoicon, but also reads JSON; each object is serialized), JSON, and YAML.