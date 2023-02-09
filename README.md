# AEMO GEL Icon
v1.1.1

GEL icon library is a collection of web icons and system icons that are custom to AEMO. This section provides guidelines on how to use the current library and create additional icons when required.

## Usage
### Install
Run the following command to install the package

```bash
npm install @danielwang/aemo-gel-icon
```

### Import 

Then import the library with the following
```js
import '@danielwang/aemo-gel-icon/style.css'
```

### Use font icons by coding in HTML

Gel icons use the `pi pi-{icon}` syntax such as pi pi-check following the reference from PrimeVue. A standalone icon can be displayed using an element like i or span.

The icons are treated as fonts. So they can be resized by giving font-size styling to the icon class.

```html
<i class="pi pi-check" style="font-size: 2rem"></i>
```

## Creating Icons

When creating new icons, consider the following guidelines to ensure consistency and accessiblity
* Use vector graphics to create icons. This will ensure that icons look sharp and clear at all times.
* Use a consistent stroke width (1.5px stroke) and line style for all icons.
* Avoid adding shading or gradinets to icons, as these can be difficult t osee fro some users.
* Ensure that icons are easily recognizable and their meaning is clear, even when viewed at small sizes.
* Consider using the [grid](https://m3.material.io/styles/icons/designing-icons#6e78ff9d-bf70-4b1d-8eab-c2058438e565) to make icons with similar weight when creating icons.
![image](https://lh3.googleusercontent.com/zYEU6tbcRdmpAzAypRZsj8z6tMpgWp0VMgGWJKL75ep5d9nB11-7vmMGJhUtuAaQiZqKVNyCPrQ8QTblK_iLeO0f3xRg0sl6cEG-WQCQdvBH=s0)


## Adding icons to the library

There can be situation where you have to create icons that are customized to your project. After creating the icons, we use [Icomoon](https://icomoon.io/) to bundle the fonticon before adding to the package for other projects to download from GEL.
The following steps can be taken to add icons to the AEMO GEL icon library using Icomoon.
* Add the icons into the collection inside Icomoon
* From the fonticon tab at the bottom of the screen, click download
* Ensure that these files are present in downloaded folder. You can check if the icons are present by opening the demo.html
```bash
├── font                    # generated font folder
├── selection.json          # json format of all the available fonticon
├── style.css               # CSS format of all the available fonticon
```
* Change the version of the library
* Consider adding an image with all the icon library including the new icons for easy scan of what fonticons are available
* Publish the changes with addition of new icon
* Upload the file to [https://github.com/danielwang/aemo-gel-icon](https://github.com/danielwang/aemo-gel-icon)


## Figma Design File 

https://www.figma.com/file/kzLxtqv6YGL0wotiqzgEo4/GEL-UI-Doc?node-id=167%3A22885&t=0c23FBxY56KakK7g-4