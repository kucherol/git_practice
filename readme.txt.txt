Const cur = prompt("Enter the currency name (EUR, USD, GBP)");
Const val = prompt("Enter the HRN amount");

If (cur == "EUR") {
alert(val/34.12 , "EUR");
} else If (cur == "USD") {
alert(val/28.30 , "USD");
} else If (cur == "GBP") {
alert(val/38.40 , "GBP");
} else {alert("Unknown data");
}


Const sum = prompt("Enter the summ of goods");

If (sum >= 200 && sum < 300) {
Alert("Summ", sum*2/100);
} else If (sum >= 300 && sum < 500) {
Alert("Summ", sum*5/100); 
} else If (sum >= 500) {
Alert("Summ", sum*7/100);
} else {
Alert("The summ is too low");
}

Const p = prompt("Enter the square perimeter");
Const l = prompt("Enter the circle length");
Const R = l/(2*3.14);
Const r = (p/4)/2;

If (r >= R) {
Alert("The circle could be inserted into the square");
} else {
Alert("The circle could not be inserted into the square");
}

Const first = prompt("What is the avarage distance from earth to the moon (km) ? Choose the correct answer: 382500, 155600, 550000.");
Const second = prompt("What is the avarage radius od the earth (km) ? Choose the correct answer: 18150, 6371, 5284.");
Const third = prompt("How fast our planet moves around the sun (km/s) ? Choose the correct answer: 100, 80, 30.");
Let points = 0;

If (first == 382500) {
Points = points+2;
} 
If (second == 6371) {
Points = points+2;
} 
If (third == 30) {
Points = points+2;
} 
If (points == 6) {
Alert(Congratulations! U are a future astronaut!! );
} else {
Alert("Sorry, your score ", points);
}

Let c = [00.00.0000];
Let c = prompt("Enter the date pls dd.mm.yyyy");


