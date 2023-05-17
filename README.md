# sneakers
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <main>
        <div id="snks">
            <img src="sneaker_350_A.jpg" alt="" class="uno" id="snk1">
            <img src="sneaker_350_B.jpg" alt="" class="dos" id="snk2">
            <img src="sneaker_350_C.jpg" alt="" class="tres" id="snk3">
            <img src="sneaker_350_D.jpg" alt="" class="cuatro" id="snk4">
        </div>
        <div>
            <img src="sneaker_1200_A.jpg" id="cont" alt="" class="Foto11">
        </div>

    </main>
    <script>
        let izk1 = document.getElementById("snk1");
        let izk2 = document.getElementById("snk2");
        let izk3 = document.getElementById("snk3");
        let izk4 = document.getElementById("snk4");
        let fotogrande = document.getElementById("cont");

        function grandeA() {
            fotogrande.setAttribute('src', 'sneaker_1200_A.jpg')

        }
        izk1.addEventListener('mouseover', grandeA);


        function grandeB() {
            fotogrande.setAttribute('src', 'sneaker_1200_B.jpg')
        }
        izk2.addEventListener('mouseover', grandeB);


        function grandeC() {
            fotogrande.setAttribute('src', 'sneaker_1200_C.jpg')
        }
        izk3.addEventListener('mouseover', grandeC);


        function grandeD() {
            fotogrande.setAttribute('src', 'sneaker_1200_D.jpg')
        }
        izk4.addEventListener('mouseover', grandeD);


    </script>

</body>

</html>
