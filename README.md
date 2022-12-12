# Metodologias CSS

## [OOCSS](http://oocss.org/) - Object-Oriented CSS

## [SMACSS](http://smacss.com/book/categorizing) (smacks)

At the very core of SMACSS is categorization. By categorizing CSS rules, we begin to see patterns and can define better practices around each of these patterns.

There are five types of categories:

1. Base
2. Layout
3. Module
4. State
5. Theme

### Base

Também conhecido como reboot, é a denição inicial dos elementos.

```
html, body, form { margin: 0; padding: 0; }
input[type=text] { border: 1px solid #999; }
a { color: #039; }
a:hover { color: #03C; }
```

### Layout

Seções da página. Estes encapsulam os módulos descritos abaixo.

### Módulos

São as partes reutilizáveis (também chamados de componentes). Exemplo sidebar.

### State

Descreve como os módulos e layots vão ser em determinadas situações, como expandido.

### Theme

Descreve a aparência do site.

### Nomenclatura

```ts
/* Example Module */
.example { }

/* Callout Module */
.callout { }

/* Callout Module with State */
.callout.is-collapsed { }

/* Form field module */
.field { }

/* Inline layout  */
.l-inline { }
```

## [BEM](https://getbem.com/introduction/)

## [Suit CSS](https://suitcss.github.io/) - Style tools for UI components
