### Features

- Proyecto utilizado para aprender a utilizar git y github a fondo.
- Todo el contenido es aleatorio sin ningun sentido mas alla del aprendisaje de git.

# Hyperblog

![](https://i2.wp.com/images.vexels.com/media/users/3/155384/isolated/lists/35a482fd8ba5072cdecc2097b412d297-smiley-kawaii-emoticon.png)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

**Table of Contents**

[TOCM]

[TOC]

#Hyperblog para aprender git

<s>Probando la edicion del readme</s>

###Code Blocks (multi-language) & highlighting

####Inline code

`$ npm install marked`

####Code Blocks (Indented style)

Indented 4 spaces, like `<pre>` (Preformatted Text).

    <?php
        echo "Hello world!";
    ?>

Code Blocks (Preformatted text):

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

####Javascript

```javascript
function test() {
  console.log("Hello world!");
}

(function () {
  var box = function () {
    return box.fn.init();
  };

  box.prototype = box.fn = {
    init: function () {
      console.log("box.init()");

      return this;
    },

    add: function (str) {
      alert("add", str);

      return this;
    },

    remove: function (str) {
      alert("remove", str);

      return this;
    },
  };

  box.fn.init.prototype = box.fn;

  window.box = box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

####HTML code

```html
<!DOCTYPE html>
<html>
  <head>
    <mate charest="utf-8" />
    <title>Hello world!</title>
  </head>
  <body>
    <h1>Hello world!</h1>
  </body>
</html>
```

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ | :-------------: | ------------: |
| col 3 is      | some wordy text |         $1600 |
| col 2 is      |    centered     |           $12 |
| zebra stripes |    are neat     |            $1 |

###FlowChart

```flow
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
```
