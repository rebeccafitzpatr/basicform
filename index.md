!DOCTYPE html

<html lang="en">

  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <meta name="keywords" content="basic, contact, modal">
  <meta name="description" content="basic website with basic contact modal">
  <meta name="author" content="Rebecca Fitzpatrick">


  <title>CDFG Art</title>

  <!--Edit cfdg to control formating-->


  <!--- Link to JavaScript plugins, needed for things like the dropdown menu to work. BOTH files are required. -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>



  <!-- Latest compiled and minified CSS -->
  <!-- Optional JavaScript -->
  <!-- jQuery first, then Popper.js, then Bootstrap JS -->
  <!---<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>

  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>




<body>

  <h1>Contact form</h1>
  
  <form>
    <label for="name">Name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email">
  
    <label for="issue">What is your issue:</label><br>
    <input type="radio" id="query" name="issue" value="query">
    <label for="male">Query</label><br>
    <input type="radio" id="feedback" name="issue" value="feedback">
    <label for="female">Feedback</label><br>
    <input type="radio" id="complaint" name="issue" value="complaint">
    <label for="female">Complaint</label><br>
    <input type="radio" id="other" name="issue" value="other">
    <label for="other">Other</label>

    <input type="submit" value="Submit">

  </form>
  

</body>

</html>
