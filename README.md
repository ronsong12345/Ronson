 <!Doctype html>
 <html>
 <!--This is code for header-->
 <h1><font color="white"><marquee>Welcome to my Gallery~ Enjoy!</marquee></font></h1>
 <!--This is code for website background-->
 <body background="wallbackground2.jpg">
 
 <!--This is code of image layout, table as layout-->
 <table style="width:100%">
 <tr>
 <th><img src="scifi1.jpg" style="width:500px;height200px;" title = "Planet Rise by AlphaSystem"></img></th>
 <th><img src="scifi2.jpg" style="width:500px;height200px;" title = "Planet Rise by STRIX"></img></th>
 <th><img src="scifi3.jpg" style="width:500px;height200px;" title = "Mister Universe by Jerry"></img></th>
 </tr>
  <tr>
 <th><img src="scifi4.jpg" style="width:500px;height200px;" title = "Space Storm by AndrieriStefano"></img></th>
 <th><img src="scifi5.jpg" style="width:500px;height200px;" title = "Space by Wildflower"></img></th>
 <th><img src="scifi6.jpg" style="width:500px;height200px;" title = "Landscape mountain by Hellica"></img></th>
 </tr>
  <tr>
 <th><img src="scifi7.jpg" style="width:500px;height200px;" title = "Tropical Paradise by AlphaSystem"></img></th>
 <th><img src="scifi8.jpg" style="width:500px;height200px;" title = "Nebula Star by JokerBoy"></img></th>
 <th><img src="scifi9.jpg" style="width:500px;height200px;" title = "Drustan Nebula by Ivana"></img></th>
 </tr>
   <tr>
 <th><img src="scifi10.jpg" style="width:500px;height200px;" title = "Nebula by AlphaSystem"></img></th>
 <th><img src="scifi11.png" style="width:500px;height200px;" title = "Eden Nebula by Starkiteckt"></img></th>
 <th><img src="scifi12.png" style="width:500px;height200px;" title = "Celestial Ember by Starkiteckt"></img></th>
 </tr>
</table>
<!--This is code of button for audio play and stop-->
 <button onclick="play()" type="button">Play</button> 
 <button onclick="stop()" type="button">Stop</button>

 <!--This ia footer code-->
 <footer>
 <p><font color="white"><Strong>Created by: Ronson Ng Yong Sheng</Strong></font></p>
 <font color="white"><p>Contact information: <a href="mailto:ronsong12345@gmail.com">ronsong12345@gmail.com</a>.</p></font>
 </footer>

 <!--This is Audio Code-->
<audio id="myAudio" autoplay>
<source src="audio.mp3" type="audio/mpeg" align="right">
</audio>

<!--javascript for stop and play audio-->
<script>
var audio = document.getElementById("myAudio");
function play() { 
    audio.autoplay = true;
    audio.load();
}

function stop() { 
    audio.autoplay = false;
    audio.load();
} 
</script>
 
 </body>
 </html>
 
 
