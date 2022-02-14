# PHP WordPress
All the code needed to convert an HTML site into a wordpress theme.

##### How about converting your favorite HTML theme to wordpress?
##### Moreover, with very easy operations, you can turn it into a wordpress theme and pull your content from here

First of all, you need to add 1 **style.css** to the main directory. You can take the first step by adding the following codes into the css and introduce your theme in wordpress.

/* <br>
Theme Name: ThemeName <br>
Version: 1.0 <br>
Author: TagMedien <br>
Author URI: https://tagmedien.de <br>
*/ <br>

There are 3 important files that you need to create first. These files are **header.php**, **footer.php** and **index.php** respectively. <br>

The **header.php** file is where you store your style files and all your design documents, including your logo and menu. <br>

The **index.php** file is your main template, the page where all your pages will be displayed and rendered. <br>

Your **footer.php** file is the file where you laid the final foundation of the page. This file is the area where your site's end texts, js and other files are hosted. <br>


You need to start your index.php page with **<?php get_header();?>**.
With this code, it will pull the codes in your site's header.php to the index.php page.
