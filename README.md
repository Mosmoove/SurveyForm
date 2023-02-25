# SurveyForm
<!DOCTYPE html>
<html lang = "en">
  <head>
    <link rel = "stylesheet" href = "styles.css">
    <meta charset = "UTF-8"> 
    <title>2022 FIFA World Cup Survey</title>
    </head>
    <body>
      <div class = "container">
<h1 id = "title">2022 FIFA World Cup Survey Form</h1>
      <p id = "description">Your opinion will help us make a difference</p>
      <form id = "survey-form">
      <fieldset>
<label id = "name-label"> Name: <input id = "name" type = "text" placeholder = "Enter your name" name = "name" required </label>
  <label id = "email-label"> Email: <input id = "email" type = "email" placeholder = "Enter your email" name = "email" required </label>
    <label id = "number-label"> Age (optional)
      <input id = "number" type = "number" placeholder = "Age" name = "age" min = "10" max = "99">
      </fieldset>
      <fieldset>
      </label>
   <label for = "dropdown">Whow will win the 2022 FIFA World Cup in Qatar?
      <select id = "dropdown" name = "dropdown">
        <option value = "">Select country </option>
        <option value = "1">Qatar</option>
        <option value = "2">Ecuador</option>
        <option value = "3">Senegal</option>
        <option value = "4">Netherlands</option>
        <option value = "6">England</option>
        <option value = "7">USA</option>
        <option value = "8">Iran</option>
        <option value = "9">Wales</option>
        <option value = "10">Argentina</option>
        <option value = "11">Poland</option>
        <option value = "12">Mexico</option>
        <option value = "13">Saudi Arabia</option>
        <option value = "14">France</option>
        <option value = "15">Denmark</option>
        <option value = "16">Tunisia</option>
        <option value = "17">Austrailia</option>
        <option value = "18">Spain</option>
        <option value = "19">Germany</option>
        <option value = "20">Japan</option>
        <option value = "21">Costa Rica</option>
        <option value = "22">Belgium</option>
        <option value = "23">Croatia</option>
        <option value = "24">Morocco</option>
        <option value = "25">Canada</option>
        <option value = "26">Brazil</option>
        <option value = "27">Serbia</option>
        <option value = "28">Switzerland</option>
        <option value = "29">Cameroon</option>
        <option value = "30">Portugal</option>
        <option value = "31">Uruguay</option>
        <option value = "32">Ghana</option>
        <option value = "33">South Korea</option>
        </select>
</label>
<h4>Who deserves to win the World Cup? Messi or Ronaldo? </h4>

<label for = "messi"> <input  value = "messi" type = "radio" name = "radio-group" id = "messi">Messi</label>
<label for = "Ronaldo"> <input id = "Ronaldo" type = "radio" name = "radio-group" value = "Ronaldo"> Ronaldo</label>
<label for = "unsure"> <input id = "unsure" type = "radio" name = "radio-group" value = "unsure">Not Sure</label>

</fieldset>

<fieldset> 
  <h4>What's your favorite World Cup in the early 21th century? (You may select more than one:)</h4>

  <label for = "2018_wc"><input id = "2010_wc" type = "checkbox" name = "improve-check" value = "2018_wc"> 2018 World Cup in Russia</label>
  <label for = "back-end">  <input id = "2014_wc" type = "2014_wc" name = "improve-check" value = "2014_wc"> 2014 World Cup in Brazil  </label>
  <label for = "2010_wc"> <input id = "2010_wc" type = "checkbox" name = "improve-check" value = "2010_wc"> 2010 World Cup South Africa </label>
  <label for = "2006_wc">  <input id = "2006_wc" type = "2006_wc" name = "improve-check" value = "2006_wc">2006 World Cup in Germany </label>
  <label for = "2002_wc"> <input id = "2002_wc" type = "2002_wc" name = "improve-check" value = "2002_wc"> 2002 World Cup in Japan/Korea </label>
 

<label for = "comment"> Any comments or suggestions?
  <textarea id = "comment" name = "comment" placeholder = "Enter your comment here..." rows = "6" cols = "60"></textarea>
  </label>

  <input id = "submit" type = "submit" name = "Submit">
  </fieldset>

        </form>
        </div>
      </body>
      
  </html>
