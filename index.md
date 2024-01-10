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
        font-size:22px;
        font-family: 'Roboto Condensed';
    }
    h2 {
      font-family: 'Roboto Condensed';
      color: #FFFFFF;
      font-size: 70px;
      font-weight: 600;
      max-width: 100%;
    }
    .main-content {color: #61f4de;
                   font-size: 22px;
        font-family: 'Roboto Condensed';
    }
    section a     {color: #61f4de;
                   font-size: 22px;
        font-family: 'Roboto Condensed';
    }
    section p     {color: #FFFFFF;
                   font-size: 18px;
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
            <div><h2> PROJECTS </h2></div>
            <div><h1>Brain Tumor CNN Project</h1><br/><a href="https://github.com/jlee92603/BrainTumor_CNN_Model/" style="color: #CCCCCC; font-size:16px"> source code link here</a>
                <p style="color:#FFFFFF"> This project builds and compiles a Convolutional Neural Network model to predict and classify different types of brain tumors from brain MRI image sets. Different hyperparameters are tested to find the set of parameters that optimizes the performance of the model. </p>
            </div>
            <div><h1>Medical Image Exploration</h1><br/><a href="https://github.com/jlee92603/medical_image_exploration" style="color: #CCCCCC; font-size:16px"> source code link here</a>
                <p style="color:#FFFFFF"> This project explores several different image analysis techniques, such as modeling medical (DICOM) image data sets and image segmentation. </p>
            </div>
        </div>
        <div class="slides">
            <div><h2 style="color: #FFFFFF"> EDUCATION </h2></div>
            <div><h1> Case Western Reserve University </h1>
                <p> Pursuing a Bachelor of Science in Engineering Degree <br/> Biomedical Engineering, Computing and Analysis Track Major with Computer Science Minor <br/> Expected Graduation: May 2025 <br/> GPA: 4.0 </p>
            </div>
            <div><h1> Korea Advanced Institute of Science and Technology (KAIST) </h1>
                <p> Studied abroad as a science engineering student during the Fall of 2022 in South Korea at KAIST. Developed an ability to adapt quickly and gained new cross cultural perspectives. </p>
            </div> 
        </div>
        <div class="slides">
            <div><h2 style="color: #FFFFFF"> CAREER </h2></div>
            <div><h1> David Wilson Research Lab</h1>
                <p> Currently working as a research assistant for a medical imaging and machine learning lab. Perform data analysis on CT DICOM images with Python and applied ML algorithms on real data sets. <br/> February 2023 - Current </p>
            </div>
            <div><h1> Capadona Research Lab </h1>
                <p> Worked as a student assistant for a lab that focuses on the development of bioinspired neural devices. Took several trainings to perform trials for neural devices. <br/> November 2021 - February 2023 </p>
            </div>
        </div>
        <div class="slides">
            <div><h2 style="color: #FFFFFF"> OTHER </h2></div>
            <div><h1> SKILLS </h1>
                <p> Programming: Python, MATLAB, Java, Github, TensorFlow, Matplotlib, Scipy, Numpy, Pydicom, Sklearn, Plotly <br/> Other Skills: Korean, Japanese, Oboe, Drum</p>
            </div>
            <div><h1> CAMBODIA VOLUNTEER </h1>
                <p> Went to Cambodia, a third world country, to teach students living in impoverished areas English, music, and dancing. Provided vital support and engaged in humanitarian work at orphanages and drug rehabilitation centers</p>
            </div>
        </div>
        <div class="slides">
            <div><h2 style="color: #FFFFFF"> CONTACT </h2></div>
            <div><p>EMAIL: jlee92603@gmail.com</p></div>
        </div>
    </div>

</body>
</html>
