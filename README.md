# Poyavlenie
<!DOCTYPE html>
<html>
<head>
<script src="http://code.jquery.com/jquery-latest.js"></script>

<script>
$(document).ready(function () {
   $("button").click(function () {
      var i=1;
      do{
    $(".p2").fadeToggle();
      i++;
   if(i%2==0){
   $(".p1").fadeToggle();}
   }
   while(i<2000)
   $(".p1").hide();
 });
});
</script>

</head>
<body>
<p class="p1"style="display:none">Выбегай поскорей</p>
<p class="p2" style="display:none">Посмотреть на снегирей.</p>
<p class="p1"style="display:none">Прилетели, прилетели,</p>
<p class="p2" style="display:none">Стайку встретили метели!</p>
<p class="p1"style="display:none">А Мороз-Красный Нос </p>
<p class="p2" style="display:none">Им рябинки принес</p>
<p class="p1"style="display:none">Хорошо угостил,</p>
<p class="p2" style="display:none">Хорошо подсластил.</p>
<p class="p1"style="display:none">Зимним вечером поздним</p>
<p class="p2" style="display:none">Ярко-алые грозди.</p>
</body>
<br><br><button>Появление четных и исчезновение нечетных</button>
</html
