<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirect Example</title>
    <style>
        body {
            margin: 0; /* Remove default margin */
        }

        .backgroundImage {
            background-image: url("https://e0.pxfuel.com/wallpapers/18/959/desktop-wallpaper-of-scenic-of-scenic-scenic-scenic-scenic-3d-scenic-of-scenic.jpg");
            background-size: cover;
            height: 100vh;
            width: 100vw;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        button {
            height: 90px;
            width: 200px;
            border-radius: 10px;
            color: black;
            background-color: burlywood;
            font-size: larger;
        }
    </style>
</head>
<body>
    <div class="backgroundImage">
        <a href="re1.html">
            <button>Click to start project</button>
        </a>
    </div>
</body>
</html>








<!DOCTYPE html>
<html lang="en">
    <head>
        <html>
            <body style="background-color:powderblue;"></body>
               
        <title> conversion of voice to text (SPEECH RECOGNIZATION) USING HTML,
            CSS,JAVASCRIPT
        </title>
        <style>
            body {
              background-color: #46659f;
            }
            
    </style>
     <style>
        div {
             border-top:inset;

           }
       </style> 
       <style>
        .center {
          text-align: center;
          color: rgba(11, 13, 118, 0.718);
        }
        </style>
         <style>
            p {
                text-align:center;
                 }
         </style>
 <h1 class="center"> Voice to Text Tool</h1>
        </html>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link
            rel="stylesheet"
            href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
            integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z"
            crossorigin="anonymous"
        />
        <link href="./styles.css" rel="stylesheet" type="text/css" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <title>Move the box with your Voice</title>
    </head>
    <body>
        <div class="main">
            <p>Please click on the mic to speek</p>
            <i class="fa fa-microphone" style="font-size:36px"></i>
             <p id ="demo"></p>
            <button id="command-button" onclick="myFunction()"  class="btn btn-primary"> 
                click On Mic</button
            >
            <h1 style="color:blue">please allow the microphone to speek</h1> 
            
 
            
             
            <p class="commands">
                Use commands such as 'Move up', 'Move down', 'Move left', 'Move
                right' .
            </p>

          
            <span id="message"></span>
            <select id="languageSelector">
                <option value="en-US">English</option>
                <option value="es-ES">Spanish</option>
                <!-- Add more language options -->
              </select>
             

        </div>
        <div class="circle-container"><div class="box"></div></div>
        
        <div class="d-flex flex-row justify-content-center">
            <textarea id="kk" class="text-center" rows="5" cols="30">
                 Text is </textarea>
                </div>
                 
 
                

                
                        <h2>Feedback Form</h2>
                        <form id="feedback-form">
                            <label for="name">Name:</label>
                            <input type="text" id="name" name="name" required>
                            
                            <label for="email">Email:</label>
                            <input type="email" id="email" name="email" required>
                            
                            <label for="message">Comments</label>
                            <textarea id="message" name="message" required></textarea>
                             <div class="rating">
                    <span class="star" data-rating="1">&#9733;</span>
                    <span class="star" data-rating="2">&#9733;</span>
                    <span class="star" data-rating="3">&#9733;</span>
                    <span class="star" data-rating="4">&#9733;</span>
                    <span class="star" data-rating="5">&#9733;</span>
                </div>
                <p>Your rating: <span id="selected-rating">0</span></p>
                            <input type="submit" value="Submit">
                        </form>
                    </div>
                </div>
            <script src="vtp.js"></script>
         
        </div>

    </body>
</html>
