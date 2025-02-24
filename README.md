<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #fce4ec;
            margin: 0;
            padding: 0;
        }
        .container {
            display: none; 
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            color:azure;
        }
        #SectionSlide1:target,
        #sectionSlide2:target,
        #SectionYesPage:target {
            display: flex;
        }
        #SectionSlide1 {
            display: flex;
        }
        a {
            margin: 10px;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
        }
        .yes { background-color: #ff4081; color: white; }
        .no { background-color: #90caf9; color: white; }
        img {
            width: 150px;
            margin-top: 20px;
        }
        .firstimg {
            background-image: url("https://i.pinimg.com/736x/ab/f5/31/abf531b90fd62e6f0ced279d988be6b7.jpg");
            background-size: cover;
            background-position: center;
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .secondimg {
            background-image: url("https://i.pinimg.com/736x/b9/73/0f/b9730fbc4c358ff001e732233b114b9d.jpg");
            background-size: cover;
            background-position: center;
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .thirdimg {
            background-image: url("https://i.pinimg.com/736x/dd/c1/00/ddc10009ec7d34b840686246d305b3a5.jpg");
            background-size: cover;
            background-position: center;
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>

    <div id="SectionSlide1" class="firstimg container">
        <h1>I wanted to tell you something, do you wish to proceed?</h1>
        <a href="#SectionYesPage" class="yes">Yes</a>
        <a href="#sectionSlide2" class="no">No</a>
    </div>
    
    <div id="sectionSlide2" class="secondimg container">
        <h1>okay</h1>
        <a href="#SectionSlide1" class="yes">back</a>
    </div>
    
    <div id="SectionYesPage" class="thirdimg container">
        <p>"Are you French? Because Eiffel for you!" ❤</p>
    </div>

</body>
</html>
