---
layout: page-background-2
---
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <style>
    body {
        background-color: #000a12;
        text-align: center;
        height: 100%;
        overflow: hidden;
    }
    .svg-wrapper {
        position: relative;
        top:50%;
        margin: 0 auto;
        width: 320px;
    }
    .shape {
      stroke-dasharray: 140 540;
      stroke-dashoffset: -474;
      stroke-width: 8px;
      fill: transparent;
      stroke: #58E6FF; 
      border-bottom: 5px solid black;
      transition: stroke-width 1s, stroke-dashoffset 1s, stroke-dasharray 1s;
    }
    .text {
      font-family: 'Roboto Condensed';
      font-size: 22px;
      line-height: 32px;
      letter-spacing: 8px;
      color: #58E6FF;
      top: -48px;
      position: relative;
    }
    .text a {color:#58E6FF;}
    .svg-wrapper:hover .shape {
      stroke-width: 2px;
      stroke-dashoffset: 0;
      stroke-dasharray: 760;
    }
    h1   { color: #58E6FF;
        font-family: 'Roboto Condensed';
    }
    .main-content {color: #58E6FF;
        font-family: 'Roboto Condensed';
    }
    section a     {color: #58E6FF;
        font-family: 'Roboto Condensed';
    }
    section p     {color: #58E6FF;
        font-family: 'Roboto Condensed';
    }
    </style>
</head>
<body>
    <div height="400" width="300">  </div>
    <div class="svg-wrapper">
        <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
            <rect class="shape" height="60" width="320" />
            <div class="text"><a href="https://jlee92603.github.io/projects">My Projects</a></div>
        </svg>
    </div>
</body>
<body>
    <div class="container">
        <div class="slides">
            <p> section 1 </p>
        </div>
        <div class="slides">
            <h2> section 2 </h2>
        </div>
        <div class="slides">
            <p> section 3 </p>
        </div>
    </div>


<a href="https://github.com/jlee92603/BrainTumor_CNN_Model/" style="color: #58E6FF"> Brain Tumor CNN Project </a>

<a href="https://github.com/jlee92603/medical_image_exploration" style="color: #58E6FF"> Medical Image Exploration </a>

<a href="https://jlee92603.github.io/projects/" style="color: #58E6FF"> Project Profile Website </a>

<p class="view"><a href="{{ site.github.owner_url }}">View My GitHub Profile</a></p>

</body>
</html>
