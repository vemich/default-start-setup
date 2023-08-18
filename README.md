# CSS Default Starter / Global Styles
+ Save time on project set up
+ Less lines of CSS

## Normalize
small CSS file that provides cross-browser consistency in the default styling of the HTML elements.

An alternative/fancier way to do this is:
```CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```
Go to [Docs] (https://necolas.github.io/normalize.css/)
+ select the latest version of normalize.css
+ Create normalize.css file in your project
+ Setup the link in the html

```HTML
<link rel="stylesheet" href="/normalize.css">```

## Fonts
#### Select Fonts
+ [fontpair] (https://www.fontpair.co/inspiration)
+ [pagecloud] (https://www.pagecloud.com/)
#### Grab the CSS
+ [typescale] (https://www.typescale.com)

Make some adjustments

## Colors
```CSS
:root {
  /* primary */
  /* grey */
  --black: #222;
  --white: #fff;
  --red-light: #f8d7da;
  --red-dark: #842029;
  --green-light: #d1e7dd;
  --green-dark: #0f5132;
}
```
#### Select Primary
Manual Approach
+ [coolors] (https://coolors.co)
+ [happyhues] (https://happyhues.co)
+ select your own color
+ get shades [shadowlord] (https://noeldelgado.github.io/shadowlord/#1e4ea3)

#### Library/Faster Approach
+ [bootstrap] (https://getbootstrap.com/docs/5.3/customize/color/)
+ [tailwind] (https://tailwindcss.com/docs/customizing-colors)

#### Select Grey
+ [tailwind] (https://tailwindcss.com/docs/customizing-colors)

#### Just go with happyhues
+ [happyhues] (https://happyhues.co)

#### Box Shadow
+ [tailwind] https://tailwindcss.com/docs/box-shadow)

#### Icons
+ [fontawesome] (https://fontawesome.com)
+ CDN link to add to your project 
```HTML
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
```
+ Check [cdnjs] (https://cdnjs.com/libraries/font-awesome) to see if a newer version is available