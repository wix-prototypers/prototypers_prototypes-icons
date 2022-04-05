# prototypers_prototypes-icons
This project helps us to add icons from different libraries in wix to our prototypes easily and conveniently.

### How to Use?
1. Copy the relevant CSS link (CDN link) to your prototype project:
<br/><br/>
```
https://cdn.jsdelivr.net/gh/wix-prototypers/prototypers_prototypes-icons@1.1/src/prototypes-icons.css
```

2. When adding icons to the prototype, we need to use the <code>&#60;i&#62;&#60;/i&#62;</code> element. This element gets the attribute **data-icon** and its value will include the library of the icon and its name.

#### Attribute Convention
<code>&#60;i data-icon="<b>library</b>-<b>iconsName</b>"&#62;&#60;/i&#62;</code>
<br/><br/>
This project includes the **wix style react** and **base ui** libraries.
To add an icon from one of those libraries:
1. Go to the [wsr](https://www.wix-style-react.com/storybook/?path=/story/foundations-foundations--icons){:target="\_blank"} / [base-ui](https://www.wix-pages.com/wix-base-ui/?path=/story/icons--inventory){:target="\_blank"} icons in the storybook sites
2. copy the icon name to the **data-icon** attribute

#### Example
```
<i data-icon="wsr-WixChat"></i>
```

### Updates
In order to update the CDN with new icons we need to generate a new css file which include all the icons from the lybrarise.
To do so, [click here](https://codepen.io/maayanp/pen/GRyOwZd){:target="\_blank"} and follow the instructions.
