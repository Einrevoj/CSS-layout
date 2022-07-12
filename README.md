<!DOCTYPE html>
<html>
<head>
	<title>CSS Layout</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
    *{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
    }
    div {
        height: 100px;
    }
    .bg-blue{
        background: blue;
    }
    .bg-black{
        background: black;
    }
    .bg-red{
        background: red;  
    }
    .bg-yellow{
        background: yellow;
    }
    .bg-green{
        background: green;
    }
    .bg-white{
        background: white;
    }
    .w-100{
        width: 100%;
    }
    .w-50{
        width: 50%;
    }
    .w-25{
        width: 25%;
    }
    .float-left{
        float: left;
    }
    .float-right{
        float: right;
    }
    .h-200{
        height: 200px;
    }
    </style>
</head>
<body>
        <div class="bg-black w-25 float-left"></div>
        <div class="bg-white w-50 float-left"></div>
        <div class="bg-black w-25 float-right"></div>
        <div class="bg-red float-left w-100"></div>
        <div class="bg-white w-25 float-left"></div>
        <div class="bg-blue w-25 float-left h-200"></div>
        <div class="bg-yellow w-25 float-left"></div>
        <div class="bg-white w-25 float-right"></div>
        <div class="bg-green w-25 float-left"></div>
</body>
