---
# the default layout is 'page'
icon: fa-solid fa-code #fas fa-crown-circle
order: 4
---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .project {
            margin-bottom: 30px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #0056b3;
        }
        h2 {
            margin-top: 0;
        }
    </style>
    <title>My Projects</title>
</head>
<body>
    <div class="project">
        <h2>Developing Voice Conversion System for Indian Languages | M.Tech Thesis</h2>
        <h3>Description:</h3>
        <ul>
            <li>Developed an End-to-End CrossLingual Voice conversion system using CycleGAN.</li>
            <li>The model aims to convert Hindi Speaker’s voice to Marathi speaker’s voice & vice-versa.</li>
        </ul>
        <h3>Status:</h3>
        <ul>
            <li>This work is submitted (under review) in the IEEE conference of Oriental COCOSDA 2023.</li>
        </ul>
        <h3>Results:</h3>
        <ul>
            <li>Results of work: <a href="https://parthkhadse.github.io/CrossLingual-VC-HI2MA/" target="_blank">View Results</a></li>
            <li>Extracted audio data from YouTube and created a Speaker Encoder to assign a unique ID for every individual speaker.</li>
        </ul>
        <a class="button" href="https://github.com/Parthkhadse/CrossLingual-VC-HI2MA" target="_blank">GitHub Repository</a>
    </div>
    <div class="project">
        <h2>Background Subtraction from Video using Local Binary Patterns | Course Project | (Oct 2022)</h2>
        <h3>Description:</h3>
        <ul>
            <li>Extracted Colour Features and texture features from frames using Local Binary Patterns.</li>
            <li>Using these features, each pixel is classified into background and foreground pixels.</li>
        </ul>
        <a class="button" href="https://github.com/Parthkhadse/Background-Subtraction-from-videos-using-Extended-Scale-Local-Binary-Patterns" target="_blank">GitHub Repository</a>
    </div>
    <div class="project">
        <h2>Neural Style Transfer | Self Project | (Jul 2020)</h2>
        <h3>Description:</h3>
        <ul>
            <li>Generated an Artistic Style image by combining content from one image and style from another image.</li>
            <li>Implemented Loss functions to preserve content and style preservation.</li>
        </ul>
        <h3>Status:</h3>
        <ul>
            <li>Leveraged pre-trained deep learning model VGG to extract content and style features from images.</li>
        </ul>
        <a class="button" href="https://github.com/Parthkhadse/Neural-Style-Transfer" target="_blank">GitHub Repository</a>
    </div>
    <div class="project">
        <h2>Implementation of Multilayered Perceptron from scratch | Self Project | (Jun 2020)</h2>
        <h3>Description:</h3>
        <ul>
            <li>Created a neural network with 1 hidden layer from scratch to classify the handwritten digits.</li>
            <li>Implemented the Gradient Descent Algorithm from scratch to optimize the weights.</li>
        </ul>
        <a class="button" href="https://github.com/Parthkhadse/Neural_Networks" target="_blank">GitHub Repository</a>
    </div>
</body>
</html>
