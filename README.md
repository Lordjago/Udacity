<!DOCTYPE html>
<html>
<head>
    <title>Pixel Art Maker!</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Monoton">
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <h1>Lab: Pixel Art Maker</h1>
   <!--  <h2>Choose Grid Size</h2>
    <form id="sizePicker">
        Grid Height:
        <input type="number" id="inputHeight" name="height" min="1" value="1">
        Grid Width:
        <input type="number" id="inputWeight" name="width" min="1" value="1">
        <input type="submit">
    </form> -->
    <h2>Pick A Color</h2>
    <div class="controls">
        <ul>
            <li class="red selected"></li>
            <li class="blue"></li>
            <li class="yellow"></li>
        </ul>

    <h2>Design Canvas</h2>
    <canvas width="600" height="400"></canvas>
    
        <button id="revealColorSelect">New Color</button>
        <div id="colorSelect">
            <span id="newColor"></span>
            <div class="sliders">
                <p>
                    <label for="red">Red</label>
                    <input id="red" name="red" type="range" min=0 max=255 value=0>
                </p>
                <p>
                    <label for="green">Green</label>
                    <input id="green" name="green" type="range" min=0 max=255 value=0>
                </p>
                <p>
                    <label for="blue">Blue</label>
                    <input id="blue" name="blue" type="range" min=0 max=255 value=0>
                </p>
            </div>
            <div>
            <button id="addNewColor">Add Color</button>
            </div>
        </div>
    </div>
    <div></div>
    <script src="jquery-3.3.1.min.js" type="text/javascript" charset="utf-8"></script>
    <script src="app.js" type="text/javascript" charset="utf-8"></script>
    <script src="designs.js"></script>
</body>
</html>
