# prototypers_prototypes-icons
![info](https://wix-prototypers.github.io/prototypers_prototypes-icons/screenshot.png)
This project helps us to add icons from different libraries in wix to our prototypes easily and conveniently.

### How to Use?
1. Copy the relevant CSS link (CDN link) to your prototype project:
<br/><br/>
```
https://cdn.jsdelivr.net/gh/wix-prototypers/prototypers_prototypes-icons@2.1/src/prototypes-icons.css
```

2. When adding icons to the prototype, we need to use the <code>&#60;i&#62;&#60;/i&#62;</code> element. This element gets the attribute **data-icon** and its value will include the library of the icon and its name.

#### Attribute Convention
<code>&#60;i data-icon="<b>library</b>-<b>iconsName</b>"&#62;&#60;/i&#62;</code>
<br/><br/>
This project includes the **wix style react** and **base ui** libraries.
To add an icon from one of those libraries:
1. Go to the [wsr](https://www.wix-style-react.com/storybook/?path=/story/foundations-foundations--icons){:target="_blank"} / [base-ui](https://www.wix-pages.com/wix-base-ui/?path=/story/icons--editor-classic-icons){:target="\_blank"} / [editor-x](https://www.wix-pages.com/wix-base-ui/?path=/story/icons--editor-x-icons){:target="\_blank"} icons in the storybook sites
2. Copy the icon name to the **data-icon** attribute

#### Examples
<table>
  <tr>
   <td>
    Library
   </td>
   <td>
    Example
   </td>
  </tr>
  <tr>
    
   <td>
      WSR
   </td>
   <td>
     <code>&#60;i data-icon="wsr-WixChat"&#62;&#60;/i&#62;</code>
   </td>
  </tr>
  <tr>
     <td>
       Base ui
     </td>
   <td>
     <code>&#60;i data-icon="base-ui-WixChat"&#62;&#60;/i&#62;</code>
   </td>
  </tr>
    <tr>
     <td>
       Editor X
     </td>
   <td>
     <code>&#60;i data-icon="editor-x-Academy"&#62;&#60;/i&#62;</code>
   </td>
  </tr>
</table>

### Updates
In order to update the CDN with new icons we need to generate a new css file which include all the icons from the libraries.
<br/>
To do so, [click here](https://codepen.io/maayanp/pen/GRyOwZd){:target="\_blank"} and follow the instructions.
