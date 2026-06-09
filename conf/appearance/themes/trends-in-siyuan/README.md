A theme that mimics the style of the Trends series of journals, with a simple and academic design. The sidebars are configured through superblocks to look very similar to the original journal articles.

## Basic Features

- Trends journal body style
    - Color scheme
    - Table styles
    - Icon caption color
- Banner at the top of the document
- Tables are centered by default
- Custom attributes: Setting `paper-part` to `abstract` will display the paragraph as an abstract.
    - Bold font
    - Blue color


## Hint

The `Trends in SiYuan` at the top of the title is a svg pseudo-element, the original image was drawn using drawio and is visible in the source src directory.

If you do not want this banner to be displayed, you can set the following css code snippet.

```css
.protyle-title::before, .protyle-title::after {
    display: none;
}

.protyle-title>div[contenteditable] {
    margin-top: unset;
}
``

