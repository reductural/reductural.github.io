---
layout: page
permalink: /resource/
title: Resource
description: 
nav: true
nav_order: 5
---


<html>

<style>
    body {
        font-family: Arial, sans-serif;
    }
    .publication {
        padding: 15px;
        margin-bottom: 5px; /* You can adjust this value to control the space between papers */
    }
    .abstract {
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.5s ease-in-out;
    }
    .abstract.open {
        max-height: 500px;  /* You can adjust this value based on your needs */
    }
    .bullet-point, .inline-abstract { /* this is for the bullet point in abstract */
        display: none;
    }
    .inline-abstract { /* this is for the bullet point in abstract */
        display: inline;
    }
    .close-lines {
        margin-bottom: 0;
    }
    .no-margin-top {
        margin-top: 0;
    }
    .bold-text {
        font-weight: bold;
        white-space: nowrap;  /* Prevents text from wrapping */
        overflow: hidden;  /* Hides text that overflows the container */
        text-overflow: ellipsis;  /* Adds an ellipsis (...) when text overflows */
    }
    .bold-text2 {
        font-weight: bold;
    }    
    .indented-content {
        margin-left: 30px;  /* You can adjust this value */
    }
</style>


<body>

<h4>Public Data on High-Skilled Immigration and International Education in the US</h4>
<p></p>

Coming soon


</body>


<script>
    function toggleAbstract(abstractId) {
        var abstractElement = document.getElementById(abstractId);
        var bulletPoint = abstractElement.querySelector('.bullet-point');
        var inlineAbstract = abstractElement.querySelector('.inline-abstract');
        
        if (abstractElement.classList.contains("open")) {
            abstractElement.classList.remove("open");
            bulletPoint.style.display = "none";
            inlineAbstract.style.display = "none";
        } else {
            abstractElement.classList.add("open");
            bulletPoint.style.display = "inline";
            inlineAbstract.style.display = "inline";
        }
    }
</script>


</html>