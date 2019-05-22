---
categories:
- general
collection: genesis-customizer
helpscout_url: https://docs.seothemes.com/article/201-how-to-prevent-transparent-header-flash-on-load
keywords: null
name: How to prevent transparent header flash on load
slug: how-to-prevent-transparent-header-flash-on-load
---
On some pages that have long load times you might notice a flash of white
before the transparent header loads. This is caused by the transparent header
body class being added too late.

To prevent this, you can add the following class on a per page basis:

    
    
    has-transparent-header  
    

This can be added to any single page or post from the **Layout Settings**
section below the content
editor:![](https://s3.amazonaws.com/helpscout.net/docs/assets/5a03f50f2c7d3a272c0d866f/images/5cc2be322c7d3a026fd41377
/file-r7Xbf1UZmq.png)

