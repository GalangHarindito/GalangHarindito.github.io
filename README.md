# GalangHarindito.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Sign Up</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
  <div class="signup_text2">Be Our Member</div>
  <div class="signup_form">
    <form>
    <fieldset>
      <br>
      <input type="text" style="padding-left: 5px;" placeholder="Full Name" maxlength="250" class="full name" id="full name">
      <br><br>  
      <input type="text" style="padding-left: 5px;" placeholder="Adress" maxlength="250" class="adress" id="adress">
      <br><br>
      <input type="text" style="padding-left: 5px;" placeholder="Phone" maxlength="250" class="phone" id="phone">
      <br><br>
      <input type="email" style="padding-left: 5px;" placeholder="email" maxlength="250" class="email" id="email">
      <br><br>
      Select Product<br>
      <select name="Products">
    b   <option value="Hot Desk"></option>
        <option value="Hot Desk">Hot Desk</option>
        <option value="Dedicated Desk">Dedicated Desk</option>
        <option value="Private Office">Private Office</option>
      </select>
      <br><br>
      <input type="number" value="duration" name="quantity" min="1" max="31">Days
      <br><br>
      <button type="button" onclick="alert('Data send to server')">Submit</button> 
    </fieldset>
  </form>
</div>



</body>
