---
 title: "Example Page"
 layout: single 
 sitemap: true 
 permalink: /examplePage/  
---
 
# Example Page

This is an example page to show what the raw version on GitHub of a few features that can be included on pages. More details can be found in the following links: [Basic Formatting](https://help.github.com/en/articles/basic-writing-and-formatting-syntax), [Advanced Formatting](https://help.github.com/en/articles/working-with-advanced-formatting), and [Mastering Markdown](https://guides.github.com/features/mastering-markdown/). When the website is ready to be published, this page can be commented out in the _navigation.yml_ file in the _\_data_ folder to remove it from the website. 

If you would like to put a image in, put the file in the _\_images_ folder and then add it in one of the following ways:
 1. If you need to resize or align the photo, you can use some basic html, like so: 

    \<p align="center">\<img src="../_images/michiganChem.png" alt="Michigan Chem Photo" width="200" />\</p>
    
    which gives:
<p align="center"><img src="../_images/michiganChem.png" alt="Michigan Chem Photo" width="200" /></p>

 2. If you don't need to format, you can insert using Markdown with:

    \!\[Michigan Chem Photo](../_images/michiganChem.png)
    
    which gives:
    
![Michigan Chem Photo](../_images/michiganChem.png)
