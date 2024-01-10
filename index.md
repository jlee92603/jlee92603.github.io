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
      stroke: #61f4de; 
      border-bottom: 5px solid black;
      transition: stroke-width 1s, stroke-dashoffset 1s, stroke-dasharray 1s;
    }
    .text {
      font-family: 'Roboto Condensed';
      font-size: 22px;
      line-height: 32px;
      letter-spacing: 8px;
      color: #61f4de;
      top: -48px;
      position: relative;
    }
    .text a {color:#61f4de;}
    .svg-wrapper:hover .shape {
      stroke-width: 2px;
      stroke-dashoffset: 0;
      stroke-dasharray: 760;
    }
    h1   { color: #61f4de;
        font-family: 'Roboto Condensed';
    }
    .main-content {color: #61f4de;
        font-family: 'Roboto Condensed';
    }
    section a     {color: #61f4de;
        font-family: 'Roboto Condensed';
    }
    section p     {color: #61f4de;
        font-family: 'Roboto Condensed';
    }
    </style>
</head>
<body>
    <div height="400" width="300">  </div>
    <div class="svg-wrapper">
        <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
            <rect class="shape" height="60" width="320" />
            <div class="text"><a href="https://github.com/jlee92603">My Github </a></div>
        </svg>
    </div>
</body>
<body>
    <div class="container">
        <div class="slides">
            <h2 style="color: #FFFFFF"> PROJECTS </h2>
            <div>
                <p></p>
                <a href="https://github.com/jlee92603/BrainTumor_CNN_Model/" style="color: #61f4de"> Brain Tumor CNN Project </a>
                <p></p>
                <a href="https://github.com/jlee92603/medical_image_exploration" style="color: #61f4de"> Medical Image Exploration </a>
                <p></p>
                <a href="https://jlee92603.github.io/projects/" style="color: #61f4de"> Project Profile Website </a> 
                <p></p>
            </div>
        </div>
        <div class="slides">
            <h2 style="color: #FFFFFF"> CAREER </h2>
        </div>
        <div class="slides">
            <h2 style="color: #FFFFFF"> SKILLS </h2>
        </div>
    </div>

</body>
</html>
