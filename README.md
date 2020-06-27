# MISIN
MISIN Webサイト構築用

## MISINとは
MISINはあなたのかわりにミシンを踏む、またはあなたにミシンの踏み方を教えるサイトです。

## サイト構成（仮）

public/
  ├ css/
  │  ├ common/
  │  │   ├ base.css
  │  │   ├ common.css /* common内のすべてのcssファイルをimportする。全てのページに反映 */
  │  │   ├ fonts.css
  │  │   ├ footer.css
  │  │   ├ header.css
  │  │   ├ layouts.css
  │  │   ├ parts.css
  │  │   └ reset.css
  │  ├ modules/
  │  │   ├ accordion.css
  │  │   └ xxx.js
  │  ├ faq.css
  │  ├ order.css
  │  ├ signin.css
  │  ├ styleguide.css
  │  ├ top.css
  │  └ works.css
  │
  ├ fonts/
  │  ├ PixelMplus10-Bold.ttf
  │  └ PixelMplus10-Regular.ttf
  │
  ├ img/
  │  ├ common/
  │  │   ├ arrow.png
  │  │   └ check_icon.png
  │  ├ top/
  │  │   ├ icon_01.png
  │  │   ├ icon_02.png
  │  │   ├ icon_03.png
  │  │   ├ icon_04.png
  │  │   ├ icon_05.png
  │  │   ├ icon_06.png
  │  │   └ main.png (→jpgのがよいかも)
  │  ├ works/
  │  │   ├ photo01.png
  │  │   └ xx_xx.png
  │  └  xxx/
  │
  ├ js/
  │  ├ common/
  │  │   ├ common.js
  │  │   ├ accordion.js
  │  │   ├ footer.js
  │  │   └ header.js
  │  ├ modules/
  │  │   ├ accordion.js
  │  │   ├ modal.js
  │  │   └ xxxx.js
  │  ├ top/
  │  │   └ top.js
  │  ├ faq/
  │  │   ├ xx.js
  │  │   └ xx_xx.js
  │  └ xxx/
  │      ├ xx.js
  │      └ xx_xx.js
  │
  ├ templates/
  │  ├ common/
  │  │   ├ footer.html
  │  │   └ header.html
  │  ├ faq/
  │  │   └ index.html
  │  ├ order/
  │  │   ├ complete.html
  │  │   ├ confirm.html
  │  │   ├ inputform_01.html
  │  │   └ inputform_02.html
  │  ├ signin/
  │  │   └ index.html
  │  ├ works/
  │  │   └ index.html
  │  │
  │  ├ index.html
  │  ├ styleguide.html
  │  │
  │  └  xxx/
  │　
  └ README.md