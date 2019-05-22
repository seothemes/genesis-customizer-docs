---
categories:
- general
collection: genesis-customizer
helpscout_url: https://docs.seothemes.com/article/199-how-to-add-theme-support-for-genesis-customizer
keywords: null
name: How to add theme support for Genesis Customizer
slug: how-to-add-theme-support-for-genesis-customizer
---
To make your child theme compatible with Genesis Customizer and prevent the
admin notice from showing, child themes need to specifically declare theme
support for Genesis Customizer. Below is a screenshot of the notice that will
be displayed if the current theme doesn't support Genesis Customizer:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/5a03f50f2c7d3a272c0d866f/images/5cad60b90428631d263bf0f8
/file-VUvhjtP7ZJ.png)

There are 2 ways to enable theme support:

### 1\. PHP: Add theme support

The first method is recommended in most cases. Place the following code
somewhere in your functions.php file:

    
    
    add_theme_support( 'genesis-customizer' );
    

### 2\. CSS: Stylesheet tag

Another option is to add a 'tag' to your stylesheets header comment. This is
how the default child theme does it, to keep the functions.php file as clean
as possible:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/5a03f50f2c7d3a272c0d866f/images/5cad67340428631d263bf105
/file-Eu9nAjoTcf.png)

