<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Forms Practise</title>
  </head>
  <body>
    <form action="post">
      <input
        type="text"
        name=""
        placeholder="Enter name"
        id=""
        maxlength=""
        minlength=""
        size=""
        value=""
        required
      />
      <!-- required works with form controls that dont give options to choose from -->
      <!-- name = pehchan of form control -->
      <!-- value = variable for data that is to be sent to server -->
      <!-- placeholder shows text until user clicks in the form control -->
      <!-- id = unique way to identify elements -->

      <input
        type="password"
        name=""
        id=""
        minlength=""
        maxlength=""
        size=""
        required
        placeholder=""
      />
      <!-- hides the data being entered -->

      <textarea name="" placeholder="" id="" cols="30" rows="10"></textarea>
      <!-- Multilint input field -->

      <input type="radio" name="1" id="11" value="must" checked />
      <input type="radio" name="1" id="12" value="must-too" />
      <input type="radio" name="1" id="13" value="must-too0" />

      <input type="checkbox" name="2" id="21" value="must" checked />
      <input type="checkbox" name="2" id="22" value="must-too" />
      <input type="checkbox" name="2" id="23" value="must-too0" />
      <!-- checked works only with radio and checkbox and is one time use only -->

      <select name="3" id="3">
        <option value="semi-must" selected>abc</option>
        <option value="semi-must-">lmnop</option>
        <option value="semi-must--">xyz</option>
      </select>
      <!-- selected only works with select and is one time use only -->

      <select name="3.0" id="3.0" multiple>
        <option value="semi-must" selected>abc</option>
        <option value="semi-must-" selected>lmnop</option>
        <option value="semi-must--" selected>xyz</option>
      </select>
      <!-- dropdown list -->

      <input
        type="file"
        name=""
        id=""
        value=""
        accept="video/*"
        data-max-size=""
      />
      <!-- Accept is Important -->

      <input type="submit" name="" value="" id="" />
      <!-- used to submmit entire form -->

      <input type="image" src="path to pic" alt="alt text" id="" />
      <!-- Get hint from image chapter -->
      <!-- alt is not partially useless -->

      <button id="" name=""><img src="" alt="" />xyz</button>
      <!-- For button with image -->

      <button disabled id="" name="">xyz</button>
      <!-- Simple button -->
      <!-- disabled stops the clickabile functionality of the form control -->

      <button type="submit">Works just like input:Submit</button>

      <input type="hidden" name="" value="" id="" />
      <!-- For devs only -->

      <input type="date" name="" id="" />
      <input type="color" name="" id="" />
      <input type="email" name="" id="" />
      <input type="url" name="" id="" />
      <input type="month" name="" id="" />
      <input type="number" name="" id="" />
      <!-- For mobile -->
      <input type="search" name="" id="" />
      <!-- Searchbox -->
      <input type="tel" name="" id="" />
      <!-- For mobile -->
      <input type="time" name="" id="" />

      <fieldset>
        <legend>xyz</legend>
        input:type=xyz
      </fieldset>
    </form>
  </body>
</html>
