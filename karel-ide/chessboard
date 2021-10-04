/* Using the 5 x 5 world in Karel IDE, I created a JS script that makes Karel (the bot) place beepers in every other space, creating a chess board pattern */
/* This was an easy level challenge in an introductory course of Javascript by Udemy */
/* My objective was to make the main function as short, organized, and least repetitive as possible */

function main(){
   chessBoard();
   lastRow();
}

function evenLine1(){
   putBeeper();
   move();
   move();
   putBeeper();
   move();
   move();
}

function oddLine2(){
   putBeeper();
   move();
   move();
   putBeeper();
   move();
}   

function moveLeftBeeper(){
   putBeeper();
   turnLeft();
   move();
   turnLeft();
   move();
}

function moveRightBeeper(){
   turnRight();
   move();
   turnRight();
}

function firstRepeat(){
   evenLine1();
   moveLeftBeeper();
}

function secondRepeat(){
   oddLine2();
   moveRightBeeper();
}

function chessBoard(){
   firstRepeat();
   secondRepeat();
   firstRepeat();
   secondRepeat();
}

function lastRow(){
   evenLine1();
   putBeeper();
}
