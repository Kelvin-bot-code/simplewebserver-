## EX01 Developing a Simple Webserver
Date:
## AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>System Specifications</title>
    <style>
        .a {
            max-width: 600px;
            margin: 50px auto;
            background-color: aquamarine;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(102, 8, 233, 0.2);
            overflow: hidden;
        }
        .b {
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .c {
            padding: 20px;
        }
        .d {
            margin-bottom: 15px;
        }
        .e {
            font-weight:bolder;
            font-size: 18px;
        }
        .f {
            font-size: 19px;
            margin-top: 5px;
            color: #020236;
        }
    </style>
</head>
<body>
    <div class="a">
        <div class="b">System Specifications</div>
        <div class="c">
            <div class="d">
                <div class="e">Device Name:</div>
                <div class="f">kelvin-PC</div>
            </div>
            <div class="d">
                <div class="e">Processor:</div>
                <div class="f">13th Gen Intel(R) Core(TM) i5-1335U @ 1.30 GHz</div>
            </div>
            <div class="d">
                <div class="e">Installed RAM:</div>
                <div class="f">16.0 GB (15.7 GB usable)</div>
            </div>
            <div class="d">
                <div class="e">Device ID:</div>
                <div class="f">15EEA3B2-7EF5-4DEC-903D-577382C3C005</div>
            </div>
            <div class="d">
                <div class="e">Product ID:</div>
                <div class="f">00342-42709-03600-AAOEM</div>
            </div>
            <div class="d">
                <div class="e">System Type:</div>
                <div class="f">64-bit operating system, x64-based processor</div>
            </div>
            <div class="d">
                <div class="e">Pen and Touch:</div>
                <div class="f">No pen or touch input is available for this display</div>
            </div>
        </div>
    </div>
</body>
</html>

## OUTPUT:
![image](https://github.com/user-attachments/assets/536bcb60-681e-4368-b4b2-c246a62d19a2)

## RESULT:
The program for implementing simple webserver is executed successfully.

