# Frontend Mentor - Recipe page solution

![](./design/desktop-preview.jpg)

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).


## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow with media queries


### What I learned

#### 1. Refining Table styles

```css
tr:last-child {
  border-bottom: none;
}
```

  - In this CSS snippet, I delved into refining table styles by targeting the last child of a table row (tr) to remove the bottom border.


```css
table {
   border-collapse: collapse;
}
```

  - The border-collapse CSS property defines the table's border model, dictating the interaction between the borders of table cells. When set to collapse, it merges adjacent table cell borders into a single border, resulting in a more compact and seamless table appearance.


```css
tr {
   border-bottom: 1px solid var(--light-grey);
}
```

  - This styling choice adds a subtle horizontal line between table rows, improving visual separation and structure.


#### 2. Customizing List 

```css
ol ::marker {
  font-weight: 700;
  color: var(--nutmeg);
}
```

  - I utilized the ::marker pseudo-element to modify the appearance of list item markers. This technique involves setting the font-weight to 700 and changing the color to a custom variable (--nutmeg).


```css
ul,
ol {
  padding-inline-start: 1.1rem;
}

li {
  padding-inline-start: 1.2rem;
  margin-block-end: 0.5rem;
}
```

  - I improved my understanding of list styling by utilizing padding-inline-start to set consistent indentation for both unordered (ul) and ordered (ol) lists. Additionally, I adjusted the padding and margin to enhance the spacing and alignment of list items (li).


## Author

- Github - [@natamellado](https://github.com/natamellado)
- Frontend Mentor - [@natamellado](https://www.frontendmentor.io/profile/natamellado)
