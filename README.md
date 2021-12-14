<!DOCTYPE html>
<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="styles.css">
    <title>Guess The Number</title>
  </head>
   <body background="images.jpg"><br>
    <h1>Guess the Number</h1>

    <p>A random number is chosen between 1 and 100. Guess it in 10 turns or fewer. This will tell you if your guess was high or low.</p>

    <div class="form">
      <label for="guessField">Enter your guess: </label><input type="text" id="guessField" class="guessField">
      <input type="submit" value="Submit guess" class="guessSubmit">
    </div>

    <div class="resultRitish">
      <p class="guesses">Previous guesses: <input type="text" id="guessField" class="guessField">  </p>
      <p class="lastResult" style="background-color: red;">Wrong!</p>
      <p class="lowOrHi">Last guess was too low!</p>
    </div>
        <script src="js.js"></script>

  

    
    

    

   
