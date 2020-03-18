<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
<style>

    
.container {
            width: 90%;
            max-height: 100%;
            padding: 20px 0 0 0;
            display: block;
            margin: 0 auto;
        }
        
        .clear {
            clear: both;
        }
        
        h1 {
            text-align: center;
            color: red;
            font-family: 'Times New Roman', Times, serif;
        }
        
        .flower {
            width: 8em;
            height: 9em;
            background-color: rgb(221, 64, 92);
            margin: 50px 0 11px 125px;
            position: relative;
        }
        
        .flower-shape1 {
            width: 8em;
            height: 5em;
            background-color: red;
            position: relative;
            top: -50px;
            border-top-right-radius: 50px;
            border-top-left-radius: 50px;
        }
        
        .flower-shape2 {
            width: 8em;
            height: 5em;
            background-color: red;
            position: relative;
            top: 50px;
            border-bottom-right-radius: 50px;
            border-bottom-left-radius: 50px;
        }
        
        .flower-shape3 {
            width: 8em;
            height: 9em;
            background-color: red;
            position: relative;
            top: -150px;
            left: 70px;
            border-top-right-radius: 50px;
            border-bottom-right-radius: 50px;
        }
        
        .flower-shape4 {
            width: 8em;
            height: 9em;
            background-color: red;
            position: relative;
            top: -294px;
            left: -70px;
            border-top-left-radius: 50px;
            border-bottom-left-radius: 50px;
            border: 3
        }
        
        .middle-shape {
            width: 8em;
            height: 8em;
            background-color: yellow;
            position: relative;
            top: -430px;
            border-radius: 50%;
            border: 3px dotted gray;
            /*********************************/
            animation-name: example;
            animation-duration: 4s;
            animation-iteration-count: infinite;
        }
        
        @keyframes example {
            0% {
                background-color: red;
            }
            25% {
                background-color: yellow;
            }
            50% {
                background-color: brown;
            }
            100% {
                background-color: rgb(109, 19, 19);
            }
        }
        
        .leaves {
            width: 8em;
            height: 9em;
            background-color: green;
        }
        
        .leave1 {
            border-radius: 0 150px 0 150px;
            float: left;
            margin-left: 32px;
            margin-top: 60px;
        }
        
        .leave2 {
            border-radius: 150px 0px 150px 0px;
            position: relative;
            top: -19em;
            left: 210px;
            float: left;
        }
        /*********
        
        .leave3 {
            border-radius: 25px 150px 50px 150px;
            float: left;
            position: relative;
            top: -15em;
            left: 25px;
        }
        **********/
        
        .tree {
            width: 2em;
            height: 20em;
            background-color: rgb(58, 179, 58);
            margin-left: 170px;
        }
        
        .root {
            width: 150px;
            height: 100px;
            background-color: gray;
            margin-left: 7em;
            border-bottom-left-radius: 50px;
            border-bottom-right-radius: 50px;
        }
        /***********
        MEDIA QUIRES
        ************/
        
        @media screen and (min-width:760px) {
            body {
                background-color: gray;
            }
            .root {
                background-color: brown;
                border-top-left-radius: 5px;
                border-top-right-radius: 5px;
                border-top-style: 1px dashed black;
            }
            .tree {
                background-color: rgb(55, 150, 55);
                width: 35px;
            }
            .container {
                width: 45%;
            }
        }
        
        @media screen and (min-width:410px) {
            .container {
                /* width: 45%; */
                display: block;
                margin: 0 auto;
            }
            body {
                background-color: gold;
            }
        }
        
        @media screen and (min-width:510px) {
            .container {
                /* width: 45%; */
                display: block;
                margin: 0 0 0 20%;
            }
            body {
                background-color: gold;
            }
        }
        
        @media screen and (max-width:370px) {
            body {
                background-color: brown;
            }
            .container {
                width: 100%;
                margin: 1% 0;
            }
        }
   

</style>
</head>

<body>

    <div class="container">
        <div class="flower">
            <div class="flower-shape1"></div>
            <div class="flower-shape2"></div>
            <div class="flower-shape3"></div>
            <div class="flower-shape4"></div>
            <div class="middle-shape"></div>
        </div>


        <div class="flower2"></div>
        <div class="leaves leave1">
        </div>
        <div class="tree"></div>
        <div class=" leaves leave2"></div>

        <!--
        <div class="leaves leave3"></div>
        -->
        <div class="root"></div>

    </div>

</body>

</html>
