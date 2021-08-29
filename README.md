![superCSS Logo](./SVGs/logo.svg)

-------

<br />

## Table of Contents
- [What is superCSS?](#what-is-supercss)
- [**Specifications and Docs**](#specifications-and-docs)
  - [**Classes**](#classes)
    - [**Positional**](#positional)
      - [Example](#example)
    - [**Borders**](#borders)
      - [Example](#example-1)
    - [**Shadows**](#shadows)
    - [**Glows**](#glows)
    - [**Backgrounds**](#backgrounds)
    - [**Gradients**](#gradients)
    - [**Miscellaneous**](#miscellaneous)
    - [**Colors**](#colors)

<br />

---------------

<br />
<br />
<br />

# What is superCSS?

superCSS is a *Tailwind* inspired, utility focused CSS framework.
Equipped with all the necessities of any web developer, superCSS
is ready to let you style at full speed for all of your web development
projects.

To import into your file as a stylesheet, use the following in the `head` of your HTML file.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/password-classified/supercss/CSS/super.css"/>
```

<br/>

**Find superCSS as `super.css` in the CSS folder!**

<br/>
<br/>
<br/>
<hr/>
<br/>
<br/>

# **Specifications and Docs**

## **Classes**
 + *Note:* with syntax descriptions, items in *[square brackets]* mean, put an integer here. Items in *{curly brackets}* mean to put a colour as seen at the bottom of this README.

### **Positional**
 - Flexbox syntax: `flex`
 - Center text syntax: `center-text`
 - Sticky element syntax: `sticky`
 - Padding syntax: `p`[size]
 - Margin syntax: `m`[size]

#### Example
```html
<div class="p3">
  <p class="m2">
    Hello World!
  </p>
</div>
```

### **Borders**
 - Round object syntax: `r`[radius]

#### Example
```html
<div class="p3 r3">
  <p class="m2">
    Hello World!
  </p>
</div>
```

### **Shadows**
 - Shadow syntax: `shadow-`[dispersion]

```html
<div class="p3 r3 shadow-5">
  <p class="m2">
    Hello World!
  </p>
</div>
```

### **Glows**
 - Glowing text syntax: `glow-text-`{colour name}
 - Glowing element syntax: `glow-`{colour name}

```html
<div class="p3 r3 shadow-5">
  <p class="m2 glow-text-orange">
    Hello World!
  </p>
</div>
```

### **Backgrounds**
 - Background colour syntax: `bg-`{colour name}

```html
<div class="p3 r3 shadow-5 bg-orangered">
  <p class="m2 glow-text-orange">
    Hello World!
  </p>
</div>
```

### **Gradients**
 - Background gradient syntax: `bg-grad-`{colour 1 name}{colour 2 name}

```html
<div class="p3 r3 shadow-5 bg-orangered">
  <p class="m2 glow-text-orange">
    Hello World!
  </p>
</div>

<div class="p3 r3 shadow-5 bg-grad-purple-orangered">
  <p class="m2 glow-text-orange">
    This has a gradient!
  </p>
</div>
```

### **Miscellaneous**
 - Navbar syntax: `nav`
 - Navbar link syntax: `nav-link`
 - Navbar Title syntax: `nav-title`

```html
<div class="p3 r3 shadow-5 bg-orangered nav sticky">
  <p class="nav-title m2 glow-text-orange">
    Navbar title
  </p>
  <p class="nav-link m2 glow-text-orange">
    Link 1
  </p>
  <p class="nav-link m2 glow-text-orange">
    Link 2
  </p>
</div>

<div class="p3 r3 shadow-5 bg-grad-purple-orangered">
  <p class="m2 glow-text-orange">
    This has a gradient!
  </p>
</div>
```

### **Colors**
There are many colours, from the Python library [ColorDict](https://pypi.org/project/colordict/), that are used for backgrounnd colour and gradients - here is a table.

| Name                 | Color                                                             |
| -------------------- | ----------------------------------------------------------------- |
| aliceblue            | <img src="https://via.placeholder.com/15/f0f8ff/000000?text=+" /> |
| alienarmpit          | <img src="https://via.placeholder.com/15/84de2/000000?text=+" />  |
| alloyorange          | <img src="https://via.placeholder.com/15/c46210/000000?text=+" /> |
| amethyst             | <img src="https://via.placeholder.com/15/64609a/000000?text=+" /> |
| antiqueruby          | <img src="https://via.placeholder.com/15/832232/000000?text=+" /> |
| antiquewhite         | <img src="https://via.placeholder.com/15/faebd7/000000?text=+" /> |
| aqua                 | <img src="https://via.placeholder.com/15/0ffff/000000?text=+" />  |
| aquamarine           | <img src="https://via.placeholder.com/15/7fffd4/000000?text=+" /> |
| aquasky              | <img src="https://via.placeholder.com/15/7bc4c4/000000?text=+" /> |
| argentina            | <img src="https://via.placeholder.com/15/74acdf/000000?text=+" /> |
| atomictangerine      | <img src="https://via.placeholder.com/15/ff9966/000000?text=+" /> |
| aztecgold            | <img src="https://via.placeholder.com/15/c39953/000000?text=+" /> |
| azure                | <img src="https://via.placeholder.com/15/f0ffff/000000?text=+" /> |
| babypowder           | <img src="https://via.placeholder.com/15/fefefa/000000?text=+" /> |
| bahamas              | <img src="https://via.placeholder.com/15/0778b/000000?text=+" />  |
| banana               | <img src="https://via.placeholder.com/15/ffd12a/000000?text=+" /> |
| bdazzledblue         | <img src="https://via.placeholder.com/15/2e5894/000000?text=+" /> |
| beige                | <img src="https://via.placeholder.com/15/f5f5dc/000000?text=+" /> |
| belgium              | <img src="https://via.placeholder.com/15/fae042/000000?text=+" /> |
| bigdiporuby          | <img src="https://via.placeholder.com/15/9c2542/000000?text=+" /> |
| bigfootfeet          | <img src="https://via.placeholder.com/15/e88e5a/000000?text=+" /> |
| bisque               | <img src="https://via.placeholder.com/15/ffe4c4/000000?text=+" /> |
| bittersweetshimmer   | <img src="https://via.placeholder.com/15/bf4f51/000000?text=+" /> |
| black                | <img src="https://via.placeholder.com/15/000/000000?text=+" />    |
| blackshadows         | <img src="https://via.placeholder.com/15/bfafb2/000000?text=+" /> |
| blanchedalmond       | <img src="https://via.placeholder.com/15/ffebcd/000000?text=+" /> |
| blastoffbronze       | <img src="https://via.placeholder.com/15/a57164/000000?text=+" /> |
| blizzardblue         | <img src="https://via.placeholder.com/15/50bfe6/000000?text=+" /> |
| blue                 | <img src="https://via.placeholder.com/15/00ff/000000?text=+" />   |
| blueberry            | <img src="https://via.placeholder.com/15/4f86f7/000000?text=+" /> |
| blueiris             | <img src="https://via.placeholder.com/15/5a5b9f/000000?text=+" /> |
| bluejeans            | <img src="https://via.placeholder.com/15/5dadec/000000?text=+" /> |
| blueturquoise        | <img src="https://via.placeholder.com/15/53b0ae/000000?text=+" /> |
| blueviolet           | <img src="https://via.placeholder.com/15/8a2be2/000000?text=+" /> |
| boogerbuster         | <img src="https://via.placeholder.com/15/dde26a/000000?text=+" /> |
| brazil               | <img src="https://via.placeholder.com/15/09b3a/000000?text=+" />  |
| brightyellow         | <img src="https://via.placeholder.com/15/ffaa1d/000000?text=+" /> |
| brown                | <img src="https://via.placeholder.com/15/a52a2a/000000?text=+" /> |
| brownsugar           | <img src="https://via.placeholder.com/15/af6e4d/000000?text=+" /> |
| bubblegum            | <img src="https://via.placeholder.com/15/ffd3f8/000000?text=+" /> |
| burlywood            | <img src="https://via.placeholder.com/15/deb887/000000?text=+" /> |
| burnishedbrown       | <img src="https://via.placeholder.com/15/a17a74/000000?text=+" /> |
| cadetblue            | <img src="https://via.placeholder.com/15/5f9ea0/000000?text=+" /> |
| cedarchest           | <img src="https://via.placeholder.com/15/c95a49/000000?text=+" /> |
| cerulean             | <img src="https://via.placeholder.com/15/9bb7d4/000000?text=+" /> |
| ceruleanfrost        | <img src="https://via.placeholder.com/15/6d9bc3/000000?text=+" /> |
| chartreuse           | <img src="https://via.placeholder.com/15/7fff0/000000?text=+" />  |
| cherry               | <img src="https://via.placeholder.com/15/da2647/000000?text=+" /> |
| chilipepper          | <img src="https://via.placeholder.com/15/9b1b30/000000?text=+" /> |
| china                | <img src="https://via.placeholder.com/15/de2910/000000?text=+" /> |
| chocolate            | <img src="https://via.placeholder.com/15/d2691e/000000?text=+" /> |
| cinnamonsatin        | <img src="https://via.placeholder.com/15/cd607e/000000?text=+" /> |
| citrine              | <img src="https://via.placeholder.com/15/93379/000000?text=+" />  |
| classicblue          | <img src="https://via.placeholder.com/15/f4c81/000000?text=+" />  |
| coconut              | <img src="https://via.placeholder.com/15/fefefe/000000?text=+" /> |
| colombia             | <img src="https://via.placeholder.com/15/fcd116/000000?text=+" /> |
| copper               | <img src="https://via.placeholder.com/15/ce8964/000000?text=+" /> |
| copperpenny          | <img src="https://via.placeholder.com/15/ad6f69/000000?text=+" /> |
| coral                | <img src="https://via.placeholder.com/15/ff7f50/000000?text=+" /> |
| cornflowerblue       | <img src="https://via.placeholder.com/15/6495ed/000000?text=+" /> |
| cornsilk             | <img src="https://via.placeholder.com/15/fff8dc/000000?text=+" /> |
| cosmiccobalt         | <img src="https://via.placeholder.com/15/2e2d88/000000?text=+" /> |
| crimson              | <img src="https://via.placeholder.com/15/dc143c/000000?text=+" /> |
| cyan                 | <img src="https://via.placeholder.com/15/0ffff/000000?text=+" />  |
| cybergrape           | <img src="https://via.placeholder.com/15/58427c/000000?text=+" /> |
| daffodil             | <img src="https://via.placeholder.com/15/ffff31/000000?text=+" /> |
| darkblue             | <img src="https://via.placeholder.com/15/008b/000000?text=+" />   |
| darkcyan             | <img src="https://via.placeholder.com/15/08b8b/000000?text=+" />  |
| darkgoldenrod        | <img src="https://via.placeholder.com/15/b886b/000000?text=+" />  |
| darkgray             | <img src="https://via.placeholder.com/15/a9a9a9/000000?text=+" /> |
| darkgreen            | <img src="https://via.placeholder.com/15/0640/000000?text=+" />   |
| darkgrey             | <img src="https://via.placeholder.com/15/a9a9a9/000000?text=+" /> |
| darkkhaki            | <img src="https://via.placeholder.com/15/bdb76b/000000?text=+" /> |
| darkmagenta          | <img src="https://via.placeholder.com/15/8b08b/000000?text=+" />  |
| darkolivegreen       | <img src="https://via.placeholder.com/15/556b2f/000000?text=+" /> |
| darkorange           | <img src="https://via.placeholder.com/15/ff8c0/000000?text=+" />  |
| darkorchid           | <img src="https://via.placeholder.com/15/9932cc/000000?text=+" /> |
| darkred              | <img src="https://via.placeholder.com/15/8b00/000000?text=+" />   |
| darksalmon           | <img src="https://via.placeholder.com/15/e9967a/000000?text=+" /> |
| darkseagreen         | <img src="https://via.placeholder.com/15/8fbc8f/000000?text=+" /> |
| darkslateblue        | <img src="https://via.placeholder.com/15/483d8b/000000?text=+" /> |
| darkslategray        | <img src="https://via.placeholder.com/15/2f4f4f/000000?text=+" /> |
| darkslategrey        | <img src="https://via.placeholder.com/15/2f4f4f/000000?text=+" /> |
| darkturquoise        | <img src="https://via.placeholder.com/15/0ced1/000000?text=+" />  |
| darkviolet           | <img src="https://via.placeholder.com/15/940d3/000000?text=+" />  |
| deeppink             | <img src="https://via.placeholder.com/15/ff1493/000000?text=+" /> |
| deepskyblue          | <img src="https://via.placeholder.com/15/0bfff/000000?text=+" />  |
| deepspacesparkle     | <img src="https://via.placeholder.com/15/4a646c/000000?text=+" /> |
| denimblue            | <img src="https://via.placeholder.com/15/2243b6/000000?text=+" /> |
| dimgray              | <img src="https://via.placeholder.com/15/696969/000000?text=+" /> |
| dimgrey              | <img src="https://via.placeholder.com/15/696969/000000?text=+" /> |
| dingydungeon         | <img src="https://via.placeholder.com/15/c53151/000000?text=+" /> |
| dirt                 | <img src="https://via.placeholder.com/15/b7653/000000?text=+" />  |
| dodgerblue           | <img src="https://via.placeholder.com/15/1e90ff/000000?text=+" /> |
| eaglegreen           | <img src="https://via.placeholder.com/15/19535f/000000?text=+" /> |
| eerieblack           | <img src="https://via.placeholder.com/15/1b1b1b/000000?text=+" /> |
| electriclime         | <img src="https://via.placeholder.com/15/ccff0/000000?text=+" />  |
| emerald              | <img src="https://via.placeholder.com/15/14a989/000000?text=+" /> |
| eucalyptus           | <img src="https://via.placeholder.com/15/44d7a8/000000?text=+" /> |
| firebrick            | <img src="https://via.placeholder.com/15/b22222/000000?text=+" /> |
| floralwhite          | <img src="https://via.placeholder.com/15/fffaf0/000000?text=+" /> |
| forestgreen          | <img src="https://via.placeholder.com/15/228b22/000000?text=+" /> |
| freshair             | <img src="https://via.placeholder.com/15/a6e7ff/000000?text=+" /> |
| fuchsia              | <img src="https://via.placeholder.com/15/ff0ff/000000?text=+" />  |
| fuchsiarose          | <img src="https://via.placeholder.com/15/c74375/000000?text=+" /> |
| gainsboro            | <img src="https://via.placeholder.com/15/dcdcdc/000000?text=+" /> |
| gargoylegas          | <img src="https://via.placeholder.com/15/ffdf46/000000?text=+" /> |
| ghostwhite           | <img src="https://via.placeholder.com/15/f8f8ff/000000?text=+" /> |
| giantsclub           | <img src="https://via.placeholder.com/15/b05c52/000000?text=+" /> |
| glossygrape          | <img src="https://via.placeholder.com/15/ab92b3/000000?text=+" /> |
| gold                 | <img src="https://via.placeholder.com/15/ffd70/000000?text=+" />  |
| goldenrod            | <img src="https://via.placeholder.com/15/daa520/000000?text=+" /> |
| goldfusion           | <img src="https://via.placeholder.com/15/85754e/000000?text=+" /> |
| granitegray          | <img src="https://via.placeholder.com/15/676767/000000?text=+" /> |
| grape                | <img src="https://via.placeholder.com/15/6f2da8/000000?text=+" /> |
| gray                 | <img src="https://via.placeholder.com/15/808080/000000?text=+" /> |
| green                | <img src="https://via.placeholder.com/15/0800/000000?text=+" />   |
| greenery             | <img src="https://via.placeholder.com/15/88b04b/000000?text=+" /> |
| greenlizard          | <img src="https://via.placeholder.com/15/a7f432/000000?text=+" /> |
| greensheen           | <img src="https://via.placeholder.com/15/6eaea1/000000?text=+" /> |
| greenyellow          | <img src="https://via.placeholder.com/15/adff2f/000000?text=+" /> |
| grey                 | <img src="https://via.placeholder.com/15/808080/000000?text=+" /> |
| honeydew             | <img src="https://via.placeholder.com/15/f0fff0/000000?text=+" /> |
| honeysuckle          | <img src="https://via.placeholder.com/15/d94f70/000000?text=+" /> |
| hotmagenta           | <img src="https://via.placeholder.com/15/ff0cc/000000?text=+" />  |
| hotpink              | <img src="https://via.placeholder.com/15/ff69b4/000000?text=+" /> |
| illuminatingemerald  | <img src="https://via.placeholder.com/15/319177/000000?text=+" /> |
| india                | <img src="https://via.placeholder.com/15/ff9a30/000000?text=+" /> |
| indianred            | <img src="https://via.placeholder.com/15/cd5c5c/000000?text=+" /> |
| indigo               | <img src="https://via.placeholder.com/15/4b082/000000?text=+" />  |
| ireland              | <img src="https://via.placeholder.com/15/ff883e/000000?text=+" /> |
| iris                 | <img src="https://via.placeholder.com/15/454ade/000000?text=+" /> |
| ivory                | <img src="https://via.placeholder.com/15/fffff0/000000?text=+" /> |
| jade                 | <img src="https://via.placeholder.com/15/469a84/000000?text=+" /> |
| jasper               | <img src="https://via.placeholder.com/15/d05340/000000?text=+" /> |
| jellybean            | <img src="https://via.placeholder.com/15/da614e/000000?text=+" /> |
| keylime              | <img src="https://via.placeholder.com/15/eaf27c/000000?text=+" /> |
| khaki                | <img src="https://via.placeholder.com/15/f0e68c/000000?text=+" /> |
| lapislazuli          | <img src="https://via.placeholder.com/15/436cb9/000000?text=+" /> |
| laserlemon           | <img src="https://via.placeholder.com/15/ffff66/000000?text=+" /> |
| latvia               | <img src="https://via.placeholder.com/15/9e3039/000000?text=+" /> |
| lavender             | <img src="https://via.placeholder.com/15/e6e6fa/000000?text=+" /> |
| lavenderblush        | <img src="https://via.placeholder.com/15/fff0f5/000000?text=+" /> |
| lawngreen            | <img src="https://via.placeholder.com/15/7cfc0/000000?text=+" />  |
| leatherjacket        | <img src="https://via.placeholder.com/15/253529/000000?text=+" /> |
| lemon                | <img src="https://via.placeholder.com/15/ffff38/000000?text=+" /> |
| lemonchiffon         | <img src="https://via.placeholder.com/15/fffacd/000000?text=+" /> |
| lichen               | <img src="https://via.placeholder.com/15/71b48d/000000?text=+" /> |
| licorice             | <img src="https://via.placeholder.com/15/1a1110/000000?text=+" /> |
| lightblue            | <img src="https://via.placeholder.com/15/add8e6/000000?text=+" /> |
| lightcoral           | <img src="https://via.placeholder.com/15/f08080/000000?text=+" /> |
| lightcyan            | <img src="https://via.placeholder.com/15/e0ffff/000000?text=+" /> |
| lightgoldenrodyellow | <img src="https://via.placeholder.com/15/fafad2/000000?text=+" /> |
| lightgray            | <img src="https://via.placeholder.com/15/d3d3d3/000000?text=+" /> |
| lightgreen           | <img src="https://via.placeholder.com/15/90ee90/000000?text=+" /> |
| lightgrey            | <img src="https://via.placeholder.com/15/d3d3d3/000000?text=+" /> |
| lightpink            | <img src="https://via.placeholder.com/15/ffb6c1/000000?text=+" /> |
| lightsalmon          | <img src="https://via.placeholder.com/15/ffa07a/000000?text=+" /> |
| lightseagreen        | <img src="https://via.placeholder.com/15/20b2aa/000000?text=+" /> |
| lightskyblue         | <img src="https://via.placeholder.com/15/87cefa/000000?text=+" /> |
| lightslategray       | <img src="https://via.placeholder.com/15/778899/000000?text=+" /> |
| lightslategrey       | <img src="https://via.placeholder.com/15/778899/000000?text=+" /> |
| lightsteelblue       | <img src="https://via.placeholder.com/15/b0c4de/000000?text=+" /> |
| lightyellow          | <img src="https://via.placeholder.com/15/ffffe0/000000?text=+" /> |
| lilac                | <img src="https://via.placeholder.com/15/db91ef/000000?text=+" /> |
| lilacluster          | <img src="https://via.placeholder.com/15/ae98aa/000000?text=+" /> |
| lime                 | <img src="https://via.placeholder.com/15/0ff0/000000?text=+" />   |
| limegreen            | <img src="https://via.placeholder.com/15/32cd32/000000?text=+" /> |
| linen                | <img src="https://via.placeholder.com/15/faf0e6/000000?text=+" /> |
| livingcoral          | <img src="https://via.placeholder.com/15/ff6f61/000000?text=+" /> |
| lumber               | <img src="https://via.placeholder.com/15/ffe4cd/000000?text=+" /> |
| macau                | <img src="https://via.placeholder.com/15/f7562/000000?text=+" />  |
| madagascar           | <img src="https://via.placeholder.com/15/fc3d32/000000?text=+" /> |
| magenta              | <img src="https://via.placeholder.com/15/ff0ff/000000?text=+" />  |
| magicmint            | <img src="https://via.placeholder.com/15/aaf0d1/000000?text=+" /> |
| magicpotion          | <img src="https://via.placeholder.com/15/ff4466/000000?text=+" /> |
| malachite            | <img src="https://via.placeholder.com/15/469496/000000?text=+" /> |
| maroon               | <img src="https://via.placeholder.com/15/8000/000000?text=+" />   |
| marsala              | <img src="https://via.placeholder.com/15/955251/000000?text=+" /> |
| mediumaquamarine     | <img src="https://via.placeholder.com/15/66cdaa/000000?text=+" /> |
| mediumblue           | <img src="https://via.placeholder.com/15/00cd/000000?text=+" />   |
| mediumorchid         | <img src="https://via.placeholder.com/15/ba55d3/000000?text=+" /> |
| mediumpurple         | <img src="https://via.placeholder.com/15/9370db/000000?text=+" /> |
| mediumseagreen       | <img src="https://via.placeholder.com/15/3cb371/000000?text=+" /> |
| mediumslateblue      | <img src="https://via.placeholder.com/15/7b68ee/000000?text=+" /> |
| mediumspringgreen    | <img src="https://via.placeholder.com/15/0fa9a/000000?text=+" />  |
| mediumturquoise      | <img src="https://via.placeholder.com/15/48d1cc/000000?text=+" /> |
| mediumvioletred      | <img src="https://via.placeholder.com/15/c71585/000000?text=+" /> |
| metallicseaweed      | <img src="https://via.placeholder.com/15/a7e8c/000000?text=+" />  |
| metallicsunburst     | <img src="https://via.placeholder.com/15/9c7c38/000000?text=+" /> |
| midnightblue         | <img src="https://via.placeholder.com/15/191970/000000?text=+" /> |
| mimosa               | <img src="https://via.placeholder.com/15/f0c05a/000000?text=+" /> |
| mintcream            | <img src="https://via.placeholder.com/15/f5fffa/000000?text=+" /> |
| mistymoss            | <img src="https://via.placeholder.com/15/bbb477/000000?text=+" /> |
| mistyrose            | <img src="https://via.placeholder.com/15/ffe4e1/000000?text=+" /> |
| moccasin             | <img src="https://via.placeholder.com/15/ffe4b5/000000?text=+" /> |
| moonstone            | <img src="https://via.placeholder.com/15/3aa8c1/000000?text=+" /> |
| mummystomb           | <img src="https://via.placeholder.com/15/828e84/000000?text=+" /> |
| mysticmaroon         | <img src="https://via.placeholder.com/15/ad4379/000000?text=+" /> |
| navajowhite          | <img src="https://via.placeholder.com/15/ffdead/000000?text=+" /> |
| navy                 | <img src="https://via.placeholder.com/15/0080/000000?text=+" />   |
| neoncarrot           | <img src="https://via.placeholder.com/15/ff9933/000000?text=+" /> |
| newcar               | <img src="https://via.placeholder.com/15/214fc6/000000?text=+" /> |
| night                | <img src="https://via.placeholder.com/15/b033/000000?text=+" />   |
| ogreodor             | <img src="https://via.placeholder.com/15/fd5240/000000?text=+" /> |
| oldlace              | <img src="https://via.placeholder.com/15/fdf5e6/000000?text=+" /> |
| olive                | <img src="https://via.placeholder.com/15/80800/000000?text=+" />  |
| olivedrab            | <img src="https://via.placeholder.com/15/6b8e23/000000?text=+" /> |
| onyx                 | <img src="https://via.placeholder.com/15/353839/000000?text=+" /> |
| orange               | <img src="https://via.placeholder.com/15/ffa50/000000?text=+" />  |
| orangered            | <img src="https://via.placeholder.com/15/ff450/000000?text=+" />  |
| orangesoda           | <img src="https://via.placeholder.com/15/fa5b3d/000000?text=+" /> |
| orchid               | <img src="https://via.placeholder.com/15/da70d6/000000?text=+" /> |
| outrageousorange     | <img src="https://via.placeholder.com/15/ff6037/000000?text=+" /> |
| palau                | <img src="https://via.placeholder.com/15/099ff/000000?text=+" />  |
| palegoldenrod        | <img src="https://via.placeholder.com/15/eee8aa/000000?text=+" /> |
| palegreen            | <img src="https://via.placeholder.com/15/98fb98/000000?text=+" /> |
| paleturquoise        | <img src="https://via.placeholder.com/15/afeeee/000000?text=+" /> |
| palevioletred        | <img src="https://via.placeholder.com/15/db7093/000000?text=+" /> |
| panama               | <img src="https://via.placeholder.com/15/da121a/000000?text=+" /> |
| pantoneemerald       | <img src="https://via.placeholder.com/15/09473/000000?text=+" />  |
| pantonerosequartz    | <img src="https://via.placeholder.com/15/f7cac9/000000?text=+" /> |
| pantoneturquoise     | <img src="https://via.placeholder.com/15/45b5aa/000000?text=+" /> |
| papayawhip           | <img src="https://via.placeholder.com/15/ffefd5/000000?text=+" /> |
| peach                | <img src="https://via.placeholder.com/15/ffd0b9/000000?text=+" /> |
| peachpuff            | <img src="https://via.placeholder.com/15/ffdab9/000000?text=+" /> |
| pearlypurple         | <img src="https://via.placeholder.com/15/b768a2/000000?text=+" /> |
| peridot              | <img src="https://via.placeholder.com/15/abad48/000000?text=+" /> |
| peru                 | <img src="https://via.placeholder.com/15/cd853f/000000?text=+" /> |
| pewterblue           | <img src="https://via.placeholder.com/15/8ba8b7/000000?text=+" /> |
| pine                 | <img src="https://via.placeholder.com/15/45a27d/000000?text=+" /> |
| pink                 | <img src="https://via.placeholder.com/15/ffc0cb/000000?text=+" /> |
| pinkpearl            | <img src="https://via.placeholder.com/15/b07080/000000?text=+" /> |
| pixiepowder          | <img src="https://via.placeholder.com/15/391285/000000?text=+" /> |
| plum                 | <img src="https://via.placeholder.com/15/dda0dd/000000?text=+" /> |
| plumppurple          | <img src="https://via.placeholder.com/15/5946b2/000000?text=+" /> |
| poison               | <img src="https://via.placeholder.com/15/37031/000000?text=+" />  |
| polishedpine         | <img src="https://via.placeholder.com/15/5da493/000000?text=+" /> |
| powderblue           | <img src="https://via.placeholder.com/15/b0e0e6/000000?text=+" /> |
| princessperfume      | <img src="https://via.placeholder.com/15/ff85cf/000000?text=+" /> |
| purple               | <img src="https://via.placeholder.com/15/80080/000000?text=+" />  |
| purpleplum           | <img src="https://via.placeholder.com/15/9c51b6/000000?text=+" /> |
| quicksilver          | <img src="https://via.placeholder.com/15/a6a6a6/000000?text=+" /> |
| radiantorchid        | <img src="https://via.placeholder.com/15/b163a3/000000?text=+" /> |
| radicalred           | <img src="https://via.placeholder.com/15/ff355e/000000?text=+" /> |
| razzledazzlerose     | <img src="https://via.placeholder.com/15/ee34d2/000000?text=+" /> |
| razzmicberry         | <img src="https://via.placeholder.com/15/8d4e85/000000?text=+" /> |
| rebeccapurple        | <img src="https://via.placeholder.com/15/663399/000000?text=+" /> |
| red                  | <img src="https://via.placeholder.com/15/ff00/000000?text=+" />   |
| redsalsa             | <img src="https://via.placeholder.com/15/fd3a4a/000000?text=+" /> |
| rose                 | <img src="https://via.placeholder.com/15/ff5050/000000?text=+" /> |
| rosedust             | <img src="https://via.placeholder.com/15/9e5e6f/000000?text=+" /> |
| rosequartz           | <img src="https://via.placeholder.com/15/bd559c/000000?text=+" /> |
| rosybrown            | <img src="https://via.placeholder.com/15/bc8f8f/000000?text=+" /> |
| royalblue            | <img src="https://via.placeholder.com/15/4169e1/000000?text=+" /> |
| ruby                 | <img src="https://via.placeholder.com/15/aa4069/000000?text=+" /> |
| rustyred             | <img src="https://via.placeholder.com/15/da2c43/000000?text=+" /> |
| saddlebrown          | <img src="https://via.placeholder.com/15/8b4513/000000?text=+" /> |
| salmon               | <img src="https://via.placeholder.com/15/fa8072/000000?text=+" /> |
| sanddollar           | <img src="https://via.placeholder.com/15/decdbe/000000?text=+" /> |
| sandybrown           | <img src="https://via.placeholder.com/15/f4a460/000000?text=+" /> |
| sapphire             | <img src="https://via.placeholder.com/15/2d5da1/000000?text=+" /> |
| sasquatchsocks       | <img src="https://via.placeholder.com/15/ff4681/000000?text=+" /> |
| screamingreen        | <img src="https://via.placeholder.com/15/66ff66/000000?text=+" /> |
| seagreen             | <img src="https://via.placeholder.com/15/2e8b57/000000?text=+" /> |
| seaserpent           | <img src="https://via.placeholder.com/15/4bc7cf/000000?text=+" /> |
| seashell             | <img src="https://via.placeholder.com/15/fff5ee/000000?text=+" /> |
| serenity             | <img src="https://via.placeholder.com/15/92a8d1/000000?text=+" /> |
| seychelles           | <img src="https://via.placeholder.com/15/fcd856/000000?text=+" /> |
| shadowblue           | <img src="https://via.placeholder.com/15/778ba5/000000?text=+" /> |
| shampoo              | <img src="https://via.placeholder.com/15/ffcff1/000000?text=+" /> |
| sheengreen           | <img src="https://via.placeholder.com/15/8fd40/000000?text=+" />  |
| shimmeringblush      | <img src="https://via.placeholder.com/15/d98695/000000?text=+" /> |
| shinyshamrock        | <img src="https://via.placeholder.com/15/5fa778/000000?text=+" /> |
| shockingpink         | <img src="https://via.placeholder.com/15/ff6eff/000000?text=+" /> |
| sienna               | <img src="https://via.placeholder.com/15/a0522d/000000?text=+" /> |
| silver               | <img src="https://via.placeholder.com/15/c0c0c0/000000?text=+" /> |
| sizzlingred          | <img src="https://via.placeholder.com/15/ff3855/000000?text=+" /> |
| skyblue              | <img src="https://via.placeholder.com/15/87ceeb/000000?text=+" /> |
| slateblue            | <img src="https://via.placeholder.com/15/6a5acd/000000?text=+" /> |
| slategray            | <img src="https://via.placeholder.com/15/708090/000000?text=+" /> |
| slategrey            | <img src="https://via.placeholder.com/15/708090/000000?text=+" /> |
| slimygreen           | <img src="https://via.placeholder.com/15/299617/000000?text=+" /> |
| smashedpumpkin       | <img src="https://via.placeholder.com/15/ff6d3a/000000?text=+" /> |
| smoke                | <img src="https://via.placeholder.com/15/738276/000000?text=+" /> |
| smokeytopaz          | <img src="https://via.placeholder.com/15/832ad/000000?text=+" />  |
| snow                 | <img src="https://via.placeholder.com/15/fffafa/000000?text=+" /> |
| soap                 | <img src="https://via.placeholder.com/15/cec8ef/000000?text=+" /> |
| solomon              | <img src="https://via.placeholder.com/15/215b33/000000?text=+" /> |
| sonicsilver          | <img src="https://via.placeholder.com/15/757575/000000?text=+" /> |
| southafrica          | <img src="https://via.placeholder.com/15/07749/000000?text=+" />  |
| springgreen          | <img src="https://via.placeholder.com/15/0ff7f/000000?text=+" />  |
| steelblue            | <img src="https://via.placeholder.com/15/4682b4/000000?text=+" /> |
| steelteal            | <img src="https://via.placeholder.com/15/5f8a8b/000000?text=+" /> |
| strawberry           | <img src="https://via.placeholder.com/15/fc5a8d/000000?text=+" /> |
| sugarplum            | <img src="https://via.placeholder.com/15/914e75/000000?text=+" /> |
| sunburntcyclops      | <img src="https://via.placeholder.com/15/ff404c/000000?text=+" /> |
| sunglow              | <img src="https://via.placeholder.com/15/ffcc33/000000?text=+" /> |
| sweetbrown           | <img src="https://via.placeholder.com/15/a83731/000000?text=+" /> |
| tan                  | <img src="https://via.placeholder.com/15/d2b48c/000000?text=+" /> |
| tangerinetango       | <img src="https://via.placeholder.com/15/dd4124/000000?text=+" /> |
| tartorange           | <img src="https://via.placeholder.com/15/fb4d46/000000?text=+" /> |
| teal                 | <img src="https://via.placeholder.com/15/08080/000000?text=+" />  |
| thistle              | <img src="https://via.placeholder.com/15/d8bfd8/000000?text=+" /> |
| tigerlily            | <img src="https://via.placeholder.com/15/e2583e/000000?text=+" /> |
| tigerseye            | <img src="https://via.placeholder.com/15/b56917/000000?text=+" /> |
| tomato               | <img src="https://via.placeholder.com/15/ff6347/000000?text=+" /> |
| truered              | <img src="https://via.placeholder.com/15/bf1932/000000?text=+" /> |
| tulip                | <img src="https://via.placeholder.com/15/ff878d/000000?text=+" /> |
| turquoise            | <img src="https://via.placeholder.com/15/40e0d0/000000?text=+" /> |
| twilightlavender     | <img src="https://via.placeholder.com/15/8a496b/000000?text=+" /> |
| ultraviolet          | <img src="https://via.placeholder.com/15/5f4b8b/000000?text=+" /> |
| usa                  | <img src="https://via.placeholder.com/15/3c3b6e/000000?text=+" /> |
| vanuatu              | <img src="https://via.placeholder.com/15/d21034/000000?text=+" /> |
| violet               | <img src="https://via.placeholder.com/15/ee82ee/000000?text=+" /> |
| wheat                | <img src="https://via.placeholder.com/15/f5deb3/000000?text=+" /> |
| white                | <img src="https://via.placeholder.com/15/ffffff/000000?text=+" /> |
| whitesmoke           | <img src="https://via.placeholder.com/15/f5f5f5/000000?text=+" /> |
| wildwatermelon       | <img src="https://via.placeholder.com/15/fd5b78/000000?text=+" /> |
| wintergreendream     | <img src="https://via.placeholder.com/15/56887d/000000?text=+" /> |
| winterwizard         | <img src="https://via.placeholder.com/15/a0e6ff/000000?text=+" /> |
| yellow               | <img src="https://via.placeholder.com/15/ffff0/000000?text=+" />  |
| yellowgreen          | <img src="https://via.placeholder.com/15/9acd32/000000?text=+" /> |
| yellowsunshine       | <img src="https://via.placeholder.com/15/fff70/000000?text=+" />  |