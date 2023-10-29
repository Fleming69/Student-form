# Student-form
it is html code for a student form.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Web Page</title>
    <link rel="stylesheet" href="form.css" /></head>

  <body id="bk">
    <section id="contact-form">
      <div id="container">
        <h2>Contact form</h2>
        <form method="POST" action="action.php">
<label for="address">Address</label>
          <br />
          <input
            name="address"
            placeholder="Address"
            id="address"
            type="text"
/>
          <p id="address_error">Address Cannot be empty</p>
<br /><br />
          City<br />
          <input name="city" id="city" placeholder="City" type="text" />
          <p id="city_error">City Cannot be empty</p>
<br /><br />
          Zip<br />
          <input name="zip" id="zip" placeholder="Zip" type="text" />
<p id="zip_error">Zip Cannot be empty</p>
          <br />

          <h2>subjects :</h2>
          <br />

<input type="checkbox" name="maths" id="maths" />
          <label for="maths">MATHS</label><br />
          <input type="checkbox" name="english" id="english" />
          <label for="english">ENGLISH</label><br />
          <input type="checkbox" name="science" id="science" />
          <label for="science">SCIENCE</label><br />
          <p class="check" id="check">Must select at least one option</p>
<h2>Homework done:</h2>

          <input name="Homework" type="radio" />YES<br />
          <input name="Homework" type="radio" />NO<br />
<p id="radio_check">My select yes or no</p>
<h2>Class:</h2>
          <select name="class" id="class">
            <option value="12th">12th</option>
            <option value="12th">11th</option>
            <option value="12th">10th</option>
          </select>
          <br />
<!-- <p id="select_check">Select one option</p> -->
<button type="submit" id="submit">Submit</button>
        </form>
      </div>
    </section>
    <script src="./Basic_form.js"></script>
  </body>
</html>
