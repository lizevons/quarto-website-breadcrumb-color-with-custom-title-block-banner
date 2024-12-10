## Problem

I am creating a website using Quarto. The website uses sidebar navigation with breadcrumbs. On some pages I would like to apply custom colours to the title block. 
I set these up in the yml header of the specific page where I would like the colours applied:

#### page.qmd
```
---
title: "Page with title-block-banner custom background"
title-block-banner: "#4097C2"
title-block-banner-color: white
---
```

The background colour is also applied to the breadcrumb section, however, the foreground (text colour) is not. I am not sure which css is applied to the breadcrumb text, 
but it seems to be the same as the body text, which is a dark colour on a light background. If you use a bright or dark banner background the breadcrumbs can be difficult to read.
Is it possible to either:

- Change the background of the breadcrumb to match the navbar
- Or change the text colour of the breadcrumb to match the title block banner text colour (`title-block-banner-color`)

The second would be my preferred option.
Here is how it renders:

![image](https://github.com/user-attachments/assets/d0789990-9f41-4543-bd5b-6ca38aab801e)

The example page is `page.qmd`.

My environment info is in `quarto-check.qmd`
