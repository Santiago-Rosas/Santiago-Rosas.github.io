---
layout: home #home si quiero poner posts  o collection si no 
permalink: /
author_profile: true
hidden: true
header:  
  overlay_color: "#5e616c"
  overlay_image: /assets/images/portadita.jpg
excerpt: >
  *Genomic and Data Scientist* <br />
intro: 
  - excerpt: '*You can find more information about my projects in my portfolio*'

feature_row:
  - image_path: /assets/images/lol3.png 
    title: "Deployment of LGBM model"
    excerpt: "Deployment of LGBM model with Continuous Training, Continuous Integration and Continuous Deployment."
    url: "https://github.com/Santiago-Rosas/Deployment-LGBMClasiffier"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  
  - image_path: /assets/images/map8.png
    title: "Bicycle accidents in Mexico City"
    excerpt: "Map describing bicycle-related accidents distributed across Mexico city districts."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  
  - image_path: /assets/images/pca.png
    title: "Clustering with K-menas"
    excerpt: "In this analysis, I employed the K-means model for Customer Personality Analysis Data."
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"   
  
  



---
{% include feature_row id="intro" type="center" %}

{% include feature_row %}

