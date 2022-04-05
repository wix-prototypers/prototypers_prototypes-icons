# prototypers_prototypes-icons
This Project helps us to add icons from different libraries in wix to our prototypes easily and conveniently

### How to Use?
1. Copy the relevant CSS link (CDN link) to your prototype project:
```
https://cdn.jsdelivr.net/gh/wix-prototypers/prototypers_prototypes-icons@1.1/src/prototypes-icons.css
```

2. When adding iccon to the prototype, we need to use the <code>&#60;i&#62;&#60;/i&#62;</code> element. This element gets the attribute: data-icon and its value will include the library of the icon and its name.

#### Convention
<code>&#60;i data-icon="library-icons name"&#62;&#60;/i&#62;</code>
This project includes the **wix style react** and **base ui** lybreries.
To add an icon from one of thoes libreires we'll need to go into the library storybook:
[wsr](https://www.wix-style-react.com/storybook/?path=/story/foundations-foundations--icons){:target="\_blank"} || [base-ui](https://www.wix-pages.com/wix-base-ui/?path=/story/icons--inventory){:target="\_blank"} and under icons you can search the icon we nned and copy its name.

#### Example
```
<i data-icon="wsr-WixChat"></i>
```

