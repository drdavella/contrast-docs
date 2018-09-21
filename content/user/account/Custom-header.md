
<!--
title: "Create a Customized Header and Footer"
description: "How to customize the header and footer styling in the UI"
tags: "user manage account header footer custom settings"
-->


Create a customized header and footer for your Contrast account with your choice color, text and more style options. 

## Header and Footer Styling

Complete the following steps to use HTML to customize the header, footer or both for your account. 

<a href="assets/images/Custom-header.png" rel="lightbox" title="Add a customized header and footer with the text and color of your choice"><img class="thumbnail" src="assets/images/Custom-header.png"/></a>

* Go to *Contrast.Data.Dir/conf*, and open the *header.html* file (to customize the header) or *footer.html* (to customize the footer).
* Add HTML content to create your own header. 
  * This file only supports inline styles (e.g., `<... style="".../>`) for the following attributes: "font-family", "background-color", "color", "font-size" and "text-decoration". 
  * You can add the attribute `align` with the following values: "center", "left", "right" and "justify".

>**Example:** <... style="font-size:20px;color:white" align="center">Your custom text here .../> 


>**Note:** The size of every header and footer is set at 50 pixels. 


### Edit the header and footer

To edit the header and footer files, update the HTML in the files and **Save** your changes. To remove the header, comment out the HTML you added or leave the file empty.
