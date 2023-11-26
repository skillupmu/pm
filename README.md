# MkDocs設定メモ

## URL

  - https://skillupmu.github.io/pm/
  - https://github.com/skillupmu/pm

## install

 - Python 3.12.0
 - Git 2.42.0.windows.2
 - Visual Studio Code 1.84.2
 - MkDocs 1.5.3
 - Material for MkDocs 9.4.10

## cmd

```
cd skillupmu/pm
mkdocs new .
mkdocs build
mkdocs serve
mkdocs gh-deploy
```

## reference

 - [Material for MkDocs公式](https://squidfunk.github.io/mkdocs-material/reference/)
 - [PyMdown Extensions Documentation公式](https://facelessuser.github.io/pymdown-extensions/)
 - [MkDocsによるドキュメント作成（個人サイト）](https://zenn.dev/mebiusbox/articles/81d977a72cee01)
 - [おもむろにメモ書き（個人サイト）](https://omomuroni.github.io/Mkdocs/00_index/)
 - [コジオン: チェス（個人サイト）](https://kojion.github.io/chess/mkdocs/001/)


## icom

  - [Material Design](https://pictogrammers.com/library/mdi/)
  - [FontAwesome](https://fontawesome.com/search?o=r&m=free)
  - [Octicons](https://primer.style/foundations/icons)
  - [Simple Icons](https://simpleicons.org/)
  - [EMOJI CHEAT SHEET](https://www.webfx.com/tools/emoji-cheat-sheet/)
  - [ICOOON MONO](https://icooon-mono.com/)
  - [Canva](https://www.canva.com/ja_jp/login/?redirect=%2Fdesign%2FDAFvAApKstw%2FRFzNffvUHeSvTd4_Bf7iBQ%2Fedit)


## admonition

```
theme:
  icon:
      admonition:
        note: 'fontawesome/solid/note-sticky'
        abstract: 'fontawesome/solid/book'
        info: 'fontawesome/solid/circle-info'
        tip: 'fontawesome/solid/bullhorn'
        success: 'fontawesome/solid/check'
        question: 'fontawesome/solid/circle-question'
        warning: 'fontawesome/solid/triangle-exclamation'
        failure: 'fontawesome/solid/bomb'
        danger: 'fontawesome/solid/skull'
        bug: 'fontawesome/solid/robot'
        example: 'fontawesome/solid/flask'
        quote: 'fontawesome/solid/quote-left'
```

!!! note "note"

    メモやノート、ポイントを記載

!!! abstract "abstract"

    要約を記載

!!! info "info"

    インフォメーションを記載

!!! tip "tip"

    tip、ヒントを記載

!!! success "success"

    成功したものを記載

!!! question "question"

    質問を記載

!!! warning "warning"

    警告を記載

!!! failure "failure"

    失敗を記載

!!! danger "danger"

    危険を記載

!!! bug "bug"

    バグ、誤りを記載

!!! example "example"

    例を記載

!!! quote "quote"

    引用を記載



## color

  - [カラーピッカー](https://lab.syncer.jp/Tool/Image-Color-Picker/)

```
red, pink, purple, deep purple, indigo(#4051b5), blue(#2094f3), light blue, cyan, teal, green, light green, lime, yellow, amber, orange, deep orange, brown, grey, blue grey, black, white
```

## yaml

 - [本サイトのyaml](https://github.com/skillupmu/pm/blob/main/mkdocs.yml)
 - [Material for MkDocs公式のyaml](https://github.com/squidfunk/mkdocs-material/blob/master/mkdocs.yml)
 - [PyMdown Extensions Documentation公式のyaml](https://github.com/facelessuser/pymdown-extensions/blob/main/mkdocs.yml)


## css

 - [本サイトのcss](https://github.com/skillupmu/pm/blob/main/docs/assets/extra.css)


## git

``` 
git remote set-url origin https://skillupmu@github.com/skillupmu/pm.git
git clone https://github.com/skillupmu/pm.git
```

## nav

``` 
nav:
  - 初期画面: index.md
  - introduction.md
  - material.md
  - section1:
      section1-1:
        section1-1-1:
          section1-1-1.md
      section1-2:
        section1-2-1:
          section1-2-1.md
  - section2:
    - page2-1.md
    - page2-2.md
```

## directory

```
pm/
├── docs/
│   ├── assets/
│   │   ├── extra.css
│   │   └── extra.js
│   ├── index.md
│   ├── 010.md
│   ├── 020.md
│   ├── 030.md
│   └── ：
├── overrides/
│   └── main.html
├── mkdocs.yml
└── site/
```

## giscus

  - https://github.com/apps/giscus
  - https://giscus.app/ja

```
<script src="https://giscus.app/client.js"
        data-repo="skillupmu/pm"
        data-repo-id="R_kgDOKxdM6w"
        data-category="Announcements"
        data-category-id="DIC_kwDOKxdM684CbNzi"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="ja"
        crossorigin="anonymous"
        async>
</script>
```

## md_in_html

```
<div class="result" markdown>
  <div class="base" markdown>

# Markdown

  </div>
</div>

```
