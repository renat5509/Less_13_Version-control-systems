<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Registration form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <form method="post">
      <h1>Registration form</h1>
      <label for="login">Login<span class="required">*</span></label>
      <input  class="input-field" id="login" type="text" name="login" placeholder="Your Name" required/>
      <label for="email">Email<span class="required">*</span></label>
      <input class="input-field"
        id="email"
        type="email"
        name="email"
        placeholder="Your Email"
        required
      />
      <label for="pass">Password<span class="required">*</span></label>
      <input class="input-field"
        id="pass"
        type="password"
        name="password"
        placeholder="min 8 char"
        minlength="8"
        required
      />
      <label for="repeat pass">Repeat password<span class="required">*</span></label>
      <input class="input-field"
        id="repeat pass"
        type="password"
        name="password"
        placeholder=""
        minlength="8"
        required
      />
      
      <label for="avatar">Your photo</label>
      <input class="input-photo" type="file" name="avatar" id="avatar" accept="image/*" placeholder=""/>
      <label for="lang">Language selection</Select></label>
      <select id="lang" name="lang-select">
        <option>ENG</option>
        <option>RUS</option>
      </select>
      <button type="submit" name="registration">OK</button>
    </form>
  </body>
</html>
