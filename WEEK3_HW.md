
<!DOCTYPE html>
<html>
<head>
	<title>Genre Title Generator</title>
</head>
<body>
<h1>Romance Genre Random Title Generator</h1>
<h3>Refresh the page for a new result and check the console.</h3>
<!-- <button type="button" onclick="clickHandler()">Generate</button>
<script type="text/javascript">
	var myPhrase = "Hello, World"
	console.log(myPhrase)
</script> -->
<script>
var romanceLocationsArray = ["Indian Resturaunt","New Delhi","Bora Bora","Junlge","coffee shop","Eiffle Tower","Statue of Liberty", "vineyard","bar"]
var romanceAdjectiveAdverbArray = ["casualy","dashingly","hopelessly","intrigued","elegantly","urgent","eagerly","bravely","happily","crazily"]
var romanceTimeOfDayArray = ["noon","evening","Night","dawn","Dusk","midnight","morning","afternnon","mid day","twilight"]
var romanceRandomLocation = romanceLocationsArray[Math.floor(Math.random() * 10)]
var romanceRandomAdjectiveAdverb = romanceAdjectiveAdverbArray[Math.floor(Math.random() * 10)]
var romanceRandomTimeOfDay = romanceTimeOfDayArray[Math.floor(Math.random() * 10)]
var genreTitleGenerator = romanceRandomLocation + " is " + romanceRandomAdjectiveAdverb + " at " + romanceRandomTimeOfDay
console.log(genreTitleGenerator)
</script>
<!-- <script>
    function clickHandler() {
      alert(genreTitleGenerator);
    }
</script> -->
</body>
</html>
