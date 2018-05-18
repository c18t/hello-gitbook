# Introduction
gitbookお試し

## Install
```sh
$ brew cask install calibre
$ yarn global add gitbook-cli
```

## Setting
[Configuration · GitBook Toolchain Documentation](https://toolchain.gitbook.com/config.html)

```json:book.json
{
    "title": "My Book",
    "author": "Author",

    "plugins": [
        "katex"
    ],
    "pluginsConfig": {
    }
}
```

## Pulugins
[Plugins for GitBook](https://plugins.gitbook.com/)

### katex
Inline math: $$\int_{-\infty}^\infty g(x) dx$$


Block math:

$$
\int_{-\infty}^\infty g(x) dx
$$

```puml
@startuml
testdot
@enduml
```

```puml
@startuml

    Class Stage1
    Class Timeout {
        +constructor:function(cfg)
        +timeout:function(ctx)
        +overdue:function(ctx)
        +stage: Stage1
    }
     Stage1 <|-- Timeout

@enduml
```