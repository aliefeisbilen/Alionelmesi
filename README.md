
<DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Youssef En-Nesyri Özür Formu</title>
  <link rel="icon" href="https://github.com/alionelmesi/test2.html/blob/main/Fenerbah%C3%A7e_SK.jpg?raw=true">
<style>
body { 
background-color: #0F052C;
background-size: cover; 
background-position: center; 
background-attachment: fixed; 

}

.kadro {
position: absolute;
top: 380px;
left:  720px;
width: 700px;
height: 300px;
border: none;
border-radius: 0%;

}

.error-image {
  display: none;
  width: 105px;
  height: 105px;
  position: absolute;
  top: 140px;
  left: 1380px;
  border: none;
border-radius: 0%;
}
.Resim{

position: absolute;
top: 600px;
left: 25px;
width: 180px;
height: 100px;
border: none;
border-radius: 0%;
}
img {
position: absolute;
top: 20px;
left: 120px;
width: 300px;
height: 280px; 
border: 5px solid #FFD700;
border-radius: 10px;
        }
h3 {
position: absolute;
left: 75px;
top: 310px;
color: #FFD700;
font-size: 22px;
} 
p{
position: absolute;
left: 50px;
top: 550px;
color: #FFD700;
font-style: italic;
font-size: 22px;

}
.yazı{
position: absolute;
left: 70px;
top: 360px;
font-style: unset;
font-size: 22px;


}
 h2{
position: absolute;
left: 880px;
top: 40px;
font-size: 40px;
color: #FFD700;
 }
li{
position: absolute;
left: 900px;
top: 100px;
font-size: 20px;
color: #FFD700;
 }
 .checkbox1 {
position: absolute;
left: 1348px;
top: 145px;
        }

.checkbox2 {
position: absolute;
left: 1348px;
top: 169px;
}

.checkbox3 {
position: absolute;
left: 1348px;
top: 191px;
}
button{
position: absolute;
left: 1305px;
top: 220px;
}

.error {
color: red;
font-size: 16px;
position: absolute;
left: 1270px;
top: 250px;
display: none; }


</style>


<script>
  function validateForm(event) {
      const checkbox1 = document.querySelector('.checkbox1');
      const checkbox2 = document.querySelector('.checkbox2');
      const checkbox3 = document.querySelector('.checkbox3');
      const errorMessage = document.getElementById('error-message');
      const errorImage = document.getElementById('error-image');
      
      if (!checkbox1.checked || !checkbox2.checked || !checkbox3.checked) {
          event.preventDefault();
          errorMessage.style.display = 'block';
          errorImage.style.display = 'inline';
      } else {
          errorMessage.style.display = 'none'; 
          errorImage.style.display = 'none';
      }
  }
</script>




</head>
<body>
  <form onsubmit="validateForm(event)">
<label> <input type="checkbox" class="checkbox1" name="option1">
</label>
<label> <input type="checkbox" class="checkbox2" name="option2">
</label>
<label> <input type="checkbox" class="checkbox3" name="option3">
</label>
<span id="error-message" class="error">İşaretle sikmim!</span>
<img id="error-image" class="error-image" src="https://github.com/alionelmesi/test2.html/blob/main/sinirli%20emoji.jpg?raw=true" alt="Error Icon">
<button type="submit">Gönder</button>
</form>
  <img src="https://github.com/alionelmesi/test2.html/blob/main/GVNYZhnWgAEE2S4.jpg?raw=true">
  <img src="https://github.com/alionelmesi/test2.html/blob/main/imza.png?raw=true" class="Resim">
  <img src="https://github.com/alionelmesi/test2.html/blob/main/fenerbah%C3%A7e%202024%20kadro.jpg?raw=true" class="kadro">

<h2>Youssef En-Nesyri Özür Formu.</h2> 
<ul>  
<li>En-Nesyri hakkında yersiz kuyu şakaları yaptım.<br>
    Karaktersiz Batshuayi'yi kendisine tercih ettim.<br>
    Kendisi hakkında çöpe atılmış 20 Milyon dedim.</li>
</ul>
<h3>Youssef En-Nesyri'den Özür Dilerim.</h3>
<p id="para1">Ali Efe İşbilen</p>
<p class="yazı">Bir daha seni eleştirmeyeceğim ve seni eleştirenlere karşı<br>
  seni savunacağım.</p>

</body>
</html>
