# Para-trolear-
Es un codigo que puedes cambiar, al ir al "No" el "No" se movera de su lugar, pero si le da al "Si" saldra un mensaje que puedes editar, si quieren usen codepen o lo que mas les guste, disfruten!!!





<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
  <title>alo</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: white;
        }
    </style>
    <script>
        function XDD(){
            alert('JAJAJAJJA q gei');
        }

        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;

            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);

            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";


        }
    </script>
</head>
<body>
  <h3>Eri gei?</h3>
    <input type="button" onclick="XDD()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
    <img src="chuec.png" width="200">
</body>
</html> 
