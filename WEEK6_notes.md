// Fun with Function

//most basic Function.
//Function Declaration or Function Defination

var ourFirstFunction = function(){
	console.log("Hello World")
}

var sayHello = function(userName){
var userName = "Priyanka"
	console.log("Hello" + userName)
}

var drawCats = function(howManyTimes){
	for (var i = 0; i < howManyTimes; i++){
	console.log(i + "=^.^=")}
}

var printMultipleTimes = function(howManyTimes, whatToDraw){
	for(var i = 0; i < howManyTimes: i++){
	console.log(i + " " + whatToDraw)
	}
}

var drawThreeCats = function(){
	console.log("Before the Return")

	return "=^.^= =^.^= =^.^="

}

var triple = funtion(passedNumberArgument){

//do something with Arguments
	var x = passedNumberArgument * 3 

	//then return the "result"
	return x
}

var fifthLetter = function(name){

	if(name.length < 5){
	return "Sorry YOur Name is Too Short, try something longer"
	}
	return "The Fifth Leyyer of Your name is " + name[4] + "."
}


var gradeForScore = function(score){
	if (score >= 90){
	return "A"
	}

	if (score < 90 && score > 80){
	return "B"
	}

	if (score < 80 && score > 70){
	return "C"
	}

	if (score < 70 && score > 60){
	return "D"
	}

	if (score < 60 && score > 50){
	return "F"
	}


}
