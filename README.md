# Promact_CSS_Assigement5
Promact Infotech Assignment 5 CSS

### Special Animation Effect

```css
### Button Enlargement on Hover:
.section-first-left button:hover {
    background-color: #0780e0;
    transform: scale(1.1);
}

### Image Box Shadow on Hover:

.section-first-right img:hover,
.section-second-left img:hover {
    box-shadow: 5px 5px 15px black;
}
### Button Width Expansion on Hover:
.button-container:hover button {
    cursor: pointer;
    width: calc(122% - 0px);
}

### Box Item Zoom on Hover:

.box-item1,
.box-item2,
.box-item3,
.box-item4,
.box-item5 {
    transition: transform 1s ease-in-out;
}

.music:hover .box-item1,
.download:hover .box-item2,
.picture:hover .box-item3,
.connect:hover .box-item4,
.location:hover .box-item5 {
    transform: scale(1.2);
}

### Live Page
