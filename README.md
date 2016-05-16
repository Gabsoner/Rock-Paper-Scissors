# Rock-Paper-Scissors
my version of a quick javascript game learned on codecademy.

+var userChoice = prompt("Do you choose Rock,Paper,Scissors?");
+var computerChoice = Math.random();
+
+if (computerChoice < 0.34){
+computerChoice = "Rock";
+if else (computerChoice = 0.67){
+computerChoice = "Paper";
+else {
+computerChoice = "Scissors";
+}
+console.log ("computer:" + computerChoice);
+var compare = function(choice1,choice2){
+if (choice1 === choice2){
+return "The result is a tie";
+}
+else if (choice1 === "Rock"){
+if (choice2 === "Paper"){
+return "Rock wins";
+}
+else
+return "Paper wins";
+}
+else if (choice1 === "Paper"){
+if (choice2 === "Rock"){
+return "Paper wins"
+}
+else
+return "Scissors wins";
+}
+else if (choice1 === "Scissors"){
+if (choice2 === "Paper"){
+return "Scissors wins";
+}
+else
+return "Rock wins";
+}
+};
+compare (userChoice,computerChoice);
