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
2. Copy the icon name to the **data-icon** attribute

#### Example
```
<i data-icon="wsr-WixChat"></i> => <svg viewBox="0 0 24 24" fill="currentColor" width="24" height="24"><path d="M12,4 C17.0881603,4 21,7.57707812 21,12 C21,13.0161605 20.7877292,14.0140623 20.3798639,14.9461513 L20.31,15.094 L20.9897765,18.3994068 C21.0529889,18.7071809 20.8215955,18.9882837 20.5206775,18.9997597 L20.4370542,18.996022 L17.173,18.581 L17.045898,18.6618802 C15.7844205,19.4147467 14.3171173,19.8677212 12.7369718,19.9751302 L12.3703621,19.9937618 L12,20 C6.91183971,20 3,16.4229219 3,12 C3,7.57707812 6.91183971,4 12,4 Z M12,5 C7.44514576,5 4,8.15032221 4,12 C4,15.8496778 7.44514576,19 12,19 C13.7930981,19 15.4391691,18.5210312 16.7884613,17.6443061 C16.8628548,17.5959677 16.9482948,17.5685852 17.0358723,17.5641977 L17.1238325,17.5675506 L19.87,17.915 L19.2982751,15.1341987 C19.2759479,15.0254903 19.2904215,14.9124432 19.3394157,14.8128662 C19.7736656,13.9302863 20,12.974619 20,12 C20,8.15032221 16.5548542,5 12,5 Z M15,11 C15.5522847,11 16,11.4477153 16,12 C16,12.5522847 15.5522847,13 15,13 C14.4477153,13 14,12.5522847 14,12 C14,11.4477153 14.4477153,11 15,11 Z M12,11 C12.5522847,11 13,11.4477153 13,12 C13,12.5522847 12.5522847,13 12,13 C11.4477153,13 11,12.5522847 11,12 C11,11.4477153 11.4477153,11 12,11 Z M9,11 C9.55228475,11 10,11.4477153 10,12 C10,12.5522847 9.55228475,13 9,13 C8.44771525,13 8,12.5522847 8,12 C8,11.4477153 8.44771525,11 9,11 Z"></path></svg>
```

### Updates
In order to update the CDN with new icons we need to generate a new css file which include all the icons from the libraries.
<br/>
To do so, [click here](https://codepen.io/maayanp/pen/GRyOwZd){:target="\_blank"} and follow the instructions.
