<html>
    <body>
        <h1>Hai Enjel</h1>
        <img src="https://https://media1.tenor.com/images/42a5caa1129d7c9bc8a592b1d00a2fe4/tenor.gif?itemid=13979931">
        <h1>Mau ga jadi pacarku?</h1>
        <button id='btn_mau' onclick='alert("I love U")'>Mau</button>&nbsp;
        <button id='btn_gamau' onclick='gamau(this)' style='position:absolute'>Gamau</button>
    </body>
    <script>
        function gamau(id){
            var mau = document.getElementById('btn_mau');
            var i = Math.floor(Math.random()*300)+1;
            var j = Math.floor(Math.random()*100)+mau.offsetTop;
            id.style.left = i+'px';
            id.style.top = j+'px';
        }
    </script>
</html>
