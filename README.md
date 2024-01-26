# html-learning
This repository contains all the content related to learning of HTML

# Elements
- Italicize: `<em>text</em>`
- Bolden: `<strong>text</strong>`
- Nesting - italicized with bold: `<em><strong>text</strong></em>`
- Void Elements: Contains a single tag, instead of opening, content and closing tag. Usually used for embedding/inserting in a document:
```
<img
  src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"
  alt="Firefox icon" />
```

### Attributes
- Elements can have attributes, which are added along with the opening tags. Multiple space-separated attributes.
- Different tags have differnt kinds of attributes. For example, `img` tag has a list of attributes which can be found [here](https://www.w3schools.com/tags/tag_img.asp)
```
<img
  src="https://media.cnn.com/api/v1/images/stellar/prod/pxl-20240117-195215998-2.jpg?c=16x9&amp;q=h_720,w_1280,c_fill"
  alt="The US Supreme Court during arguments in Relentless Inc v. Department of Commerce on Wednesday, January 17, 2024."
  height="160" width="284" loading="lazy" pinger-seen="true"
/>
```
- Some attributes can also be **boolean**, in which case we don't need to provide different attribute name and value. Example:
  ```
  <input type="text" disabled="disabled" />
  ```
  Or
  ```
  <input type="text" disabled />
  ```
  This will grey out the text input area.
- Use anchors elements for Hyperlinks.
  ```
  <a href=https://www.mozilla.org/ title="Mozilla Homepage">
    favorite websitse
  </a>
  ```
  `title` attribute shows the text while hovering the mouse over, while the content ("favorite website") shows the text on the webpage.\
  **Quotes** in the text is done using `&quot;`, as in this example: \
  `<a href="https://www.mozilla.org/" title="Here &quot;it&quot; is">favorite websitse</a>`: This will show the text on hovering `Here "it" is`
- 
  
### Head
- `<title>` is used in the google search results hyperlink and also used in bookmarks. `<meta name="description" value="It's the text below link in Google search result">`
- `<link rel="stylesheet" href="my-css-file.css" />` and `<script src="my-js-file.js" defer></script>` are also used in the head element to add CSS styling.
  > NOTE: In case of `<script>`, we can also put the css script directly into the element, instead of using a source file from a different location.
- Charset meta attribute is used for character encoding: `<meta charset="utf-8" />` and `utf-8` is considered the standard encoding supporting most of the characters.
  > Note: `charset` encoding is different from the `lang` attribute used in the `html` element, it's used by the search engines for effective indexing, and helps with the language specific search results.
#### `<meta>` tags
  - `<meta>` tags are used in head elements for metadata and contains some global attributes applied to the whole document, like `charset` and `name`.
##### [`viewport`](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag)
  - It is used for the area in which web content can be seen. It's usually different from the rendered page size.
  - Notable attributes of viewport are `width`, `height`, `initial-scale`, `minimum-scale`, `maximum-scale`, `user-scaleable`, `interactive-widget`.
  - Usually to make the content appear similar on different devices (mobile, desktop etc.), `width` (determines the size of viewport) and `initial-scale` (determines the zoom level) attributes are used:\
      `<meta name="viewport" content="width=device-width, initial-scale=1" />`

### CSS
- 















