# COP1000_algebra_exercises
Basic algebra and algorithms exercises to do in class

## 1) Can you restate the conditional more simply?
```javascript
if ((isMichaelPhelps || isMerman) && (isMichaelPhelps || hasGills))
	winGoldMedals();
```

## 2) Can you restate the conditional to use only one negation?
```javascript
if (!rich && !happy) 
	killSelf();
else 
	liveOn();
```

## 3) Can you restate the condition to use two negations and be more legible?
```javascript
if (!(urgent && important)) 
	usePostOfice();
else 
	useFedex();
```

## 4) Under which circumstances will doSomething run?
```javascript
if (x > 5 && x <= -5) 
	doSomething();
```

## 5) Under which circumstances will doSomething run?
```javascript
if (x > 5 || x <= -5) 
	doSomething();
```

## 6) Can you restate the conditional to use no negations?
```javascript
if ( !(x > 10 && y < 15))
	alert("You got it!");
else
	prompt("What you need?");
```

## 7) Can you restate the conditional to use only one negation?
```javascript
if (!(x < 10) || y <= 10 || z <= 25 || !dead) {
	console.log("You know your DeMorgan's Laws");
}
```

## 8) Can you distribute the negation across the expression in parens?
```javascript
if (!(!alive || distance > 1000 || trapped || enemies < 0)) {
	alert("game goes on");
}
```

## 9) Can you distribute the negation across the expression in parens?
```javascript
if (!(dead && level < 99 && world == "Earth")) {
	alert ("Life goes on");
}
```

## 10) In programming, what is the opposite of black?

## 11) In programming, what is the opposite of x > y ?

## 12) Generate a random number between 0 and 1 in Javascript

## 13) Generate a random number between 0 and 10 in Javascript

## 14) Generate a random integer between 0 and 10 (inclusive)

## 15) Generate a random number between 5 and 10

## 16) Generate a random integer between 5 and 10

## 17) Generate a random integer between -10 and 30

## 18) Write a coin flip function. It should return the string "heads" half the time and the string "butts" the other half
```javascript
function coinFlip(){

}
```

## 19) Write a card picking function that outputs cards from a standard deck: ex 'Ace of Clubs', 'Queen of Hearts', '10 of Diamonds', '8 of Spades'
There are 4 suits: Hearts, Diamonds, Clubs, Spades
There are 13 cards for each suit: Ace, 2-10, Jack, King, Queen
steps:
1. generate a random number between 1-4 for suit
2. set the value of a string variable depending on that 1-4 number
3. generate a random number between 1-13 for the card's number
4. put the number and the suit string together and return it
```javascript
function pickCard(){
	var suit = Math.round(Math.random()*3);
	if (suit === 0) suit = "Hearts";
	else if (suit === 1) suit = "Diamonds";
	else if (suit === 2) suit = "Clubs";
	else suit = "Spades";

	//your code here

	return suit;
}
```

## 20) Given an array of numbers, add up all the elements
```javascript
var a = [5,6,7,5433,543,53,535,53,543,543,23,412,34,45];
19) Write a function has1337s() which takes an array and returns true if the array contains the number 1337
function has1337s(arr){
	for (var i =0; i <arr.length; i++) {
	if (arr[i] == 1337) return true;
	}
	return false;
}
```

## 21) Write a function that receives an array and another parameter.
It will return true if one of the elements of the array is
equal to the other param. It should return false otherwise
```javascript
function containsThing(arr,theThing){

}
```

## 22) Write a function that receives an array and another parameter. It will return true if NONE of the elements of the array is equal to the other param. It should return false otherwise
```javascript
function doesntContain(arr, theThing){

}
```

## 23) Write a function that receives an array of numbers and returns the average of those numbers
```javascript
function getAvg(arr){
	
}
```

## 24) Write a function which draws a star triangle based on an input number
```javascript
starz(2) =
**
*
starz(4) =
****
***
**
*
```

## 25) Write a function which receives a parameter n and returns the sum of its half plus half of that, plus half of that, until You reach a number lower than 2
```javascript
n = 100, result = 50+25+12.5+6.25+3.125+1.5625;
n = 64, result = 32+16+8+4+2+1;

function sumHalves(n){

}
```
