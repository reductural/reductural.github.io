---
layout: page
permalink: /teaching/
title: Teaching
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

<h4>Princeton University</h4>
<p></p>

<div class="publication" id="t3">
    <span>2017 Spring</span><br>
    <span class="bold-text">ECO 313 Econometric Applications</span><br>
    <span>Recitation lecturer for Professor Henry Farber</span><br>
    <span>Evaluation: 4.1/5.0 (department-wide average: 3.6)</span><br>
    <span class="bold-text"><i>Course contents</i>:</span><span> Event study, panel models, IV, diff-in-diff, RD, time series, binary and multinomial choice models, measurement error, censored data, ordered response</span><br>
</div>

<div class="publication" id="t2">
    <span>2016 Spring</span><br>
    <span class="bold-text">ECO 313 Econometric Applications</span><br>
    <span>Recitation lecturer for Professor Michal Kolesar and Professor Mark Watson</span><br>
    <span>Evaluation: 4.9/5.0 (department-wide average: 4.0)</span><br>
    <span class="bold-text"><i>Course contents</i>:</span><span> OLS, panel models, IV, diff-in-diff, RD, time series, VAR, binary and multinomial choice models</span><br>
</div>

<div class="publication" id="t1">
    <span>2015 Fall</span><br>
    <span class="bold-text">ECO 302 Econometrics</span><br>
    <span>Recitation lecturer for Professor Kirill Evdokimov</span><br>
    <span>Evaluation: 3.9/5.0 (department-wide average: 3.7)</span><br>
    <span class="bold-text"><i>Course contents</i>:</span><span> “Introduction to Econometrics” by Stock and Waston</span><br>
</div>

<!--<p></p>
Complete teaching evaluations -->
<p></p>

<span class="bold-text">Selected student comments:</span><br>
<p></p>
<ul>
    <li>“Mingyu was by far the best preceptor I've ever had at Princeton. He was incredibly helpful understanding the economic intuition behind the problem sets. He devoted a lot of time to helping us understand the class and we greatly appreciate him!!!!!!!!”</li>
    <li>“Mingyu Chen has been an extraordinary preceptor: always available for clarification, both personally and via email, well prepared, and extremely kind. This has been vital especially has the workload for problem sets was huge.”</li>
    <li>“Mingyu was very organized in his approach, making precepts a very efficient learning process. These were some of the most informative I have had.”</li>
    <li>“Mingyu was a rock star! he was so helpful, patient, and good at explaining tough concepts.”</li>
</ul>



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