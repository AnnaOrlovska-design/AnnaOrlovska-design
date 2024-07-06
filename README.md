<a href="https://www.facebook.com/Pizzeriadapaolinomalilla/" target="_blank"><img src="facebook.png" title="síguenos en Facebook" alt="logo de facebook" width="50px"></a><a href="https://www.instagram.com/da_paolino/?hl=es" title="Síguenos en Instagram" target="_blank"><img src="instagram.png" width="40px" alt="logo de Instagram" style="margin-left: 10px"></a></p>

<!--   <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p> -->

  </div>

  <div class="logoFooter">

    <img src="logo_footer.png" alt="Pizzeria DaPaolino">

  </div>

</footer>

<script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script><script  src="script.js"></script>

<script>

// Tabbed Menu

function openMenu(evt, menuName) {

  var i, x, tablinks;

  x = document.getElementsByClassName("menu");

  for (i = 0; i < x.length; i++) {

    x[i].style.display = "none";

  }

  tablinks = document.getElementsByClassName("tablink");

  for (i = 0; i < x.length; i++) {

    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");

  }

  document.getElementById(menuName).style.display = "block";

  evt.currentTarget.firstElementChild.className += " w3-dark-grey";

}

document.getElementById("myLink").click();

</script>



</body>

</html>
