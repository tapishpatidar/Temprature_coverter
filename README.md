<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="temp.css">
</head>

<body>
    <div class="temp-top" id="temp-top1">
        <div class="temp-bg">
            <div class="cover">
                <div id="form">
                    <label for="celcius">Celcius</label>
                    <input type=" number" id="celcius"  placeholder="Enter Celcius">
                    <button class="button" onclick="converttoFahrenheit()">Converttofahrenheit</button>
                    <br><br>
                    <label for="fahrenheit">Fahrenheit</label>
                    <input type=" number" id="fahrenheit"  placeholder="Enter Fahrenheit"
                    >
                    <button class="button" onclick="converttoCelcius()">Converttocelcius</button>
                    <br><br>

                    <button class="button" onclick="reset()">Reset</button>

                </div>
            </div>
        </div>

    </div>

<script src="temp.js"></script>
</body>

</html>
