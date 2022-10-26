---
id: bd7158d8c242eddfaeb5bd13
title: Build a Survey Form
isRequired: true
challengeType: 1
isHidden: false
---

## HTML
```

<!DOCTYPE html>
<html>
  <head>
    <title>Survey Form</title>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
      <h1 id="title">freeCodeCamp Survey Form</h1>
      <p id="description"><em>Thank you for taking the time to help us improve the platform</em></p>
    </header>

    <br>
    <br>

    <main>
      <form id="survey-form">
          <label for="name" id="name-label">Name <input id="name" type="text" required placeholder="Enter your name"/></label>
          
          <hr>

          <label for="email" id="email-label">Email <input id="email" type="email" required placeholder="Enter your Email"/></label>

          <hr>

          <label for="number" id="number-label">Age (optional) <input id="number" type="number" min="13" max="100" placeholder="Age"/></label>

          <hr>

          <label for="dropdown" >Which option best describes your current role?
            <br>
            <br>
            <select id="dropdown">
              <option value="0" >Select current role</option>
              <option value="1">Student</option>
              <option value="2">Full Time Job</option>
              <option value="3">Full Time Learner</option>
              <option value="4">Prefer not to say</option>
              <option value="5">Other</option>
            </select>
          </label>

          <hr>

        <label>Would you recommend freeCodeCamp to a friend?
          <br>
          <br>
          <input id="definitely" type="radio" name="radiogroup" value="0"/> Definitely</label>

        <br>

        <label for="maybe"><input id="maybe" type="radio" name="radiogroup" value="1"/> Maybe</label>
        
        <br>

        <label for="not-sure"><input id="not-sure" type="radio" name="radiogroup" value="2"/> Not sure</label>

        <hr>

        <label for="dropdown" >What is your favorite feature of freeCodeCamp?
          <br>
          <br>
            <select id="dropdown">
              <option value="0" >Select an option</option>
              <option value="1">Challenges</option>
              <option value="2">Projects</option>
              <option value="3">Community</option>
              <option value="4">Open Source</option>>
            </select>
        </label>

        <hr>

        <label>What would you like to see improved? (Check all that apply)
          <br>
          <br>
          <label for="fep">
            <input id="fep" type="checkbox" value="0"/> Front-end Projects
          </label>
          <br>
          <label for="bep">
            <input id="bep" type="checkbox" value="1"/> Back-end Projects
          </label>
          <br>
          <label for="da">
            <input id="da" type="checkbox" value="2"/> Data Visualisation
          </label>
        </label>

        <hr>

        <label for="comment">Any comments or suggestions?  
          <br>
          <br>
          <textarea id="comment" rows="10" cols="52" placeholder="Enter your comment here..."></textarea>
        </label>

        <hr>

          <input type="submit" id="submit" class="submit">
      </form>
    </main>
  </body>
</html>

```

## CSS
```

body {
      font-family: 'Lato', 'Lucida Grande', 'Lucida Sans Unicode', Tahoma, Sans-Serif;
      background: rgb(10.59%, 10.59%, 19.61%);
      color: white;
}

header{
  margin-top: 60px;
  text-align: center;
}

.submit{
  margin-bottom: 40px;
}

.main {
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    color: #ffffff;
    overflow-y: scroll;
    font-size: 24px
}

.main::after {
    content: "";
    background-color: rgb(0, 0, 0,.8);
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
}

.main > h1,
.main > p {
  text-align: center;
  font-family: 35px;
  z-index: 2;
  position: relative
}

.main-content {
  background-color: rgb(27, 27, 50, .9);
    max-width: 650px;
    display: flex;
    flex-direction: column;
    padding: 40px;
    margin: 0 auto;
  margin-bottom: 40px;
    border-radius: 5px;
    z-index: 2;
    position: relative;
      box-shadow: 0px -1px 10px 5px purple;
}

#name, #email, #number, #dropdown, #comment {
    display: block;
    width: 100%;
    height: 35px;
    padding: 5px 10px;
    color: #000000;
    background-color: #ffffff;
    border: 1px solid #eeeeee;
    border-radius: 5px;
    font-size: 20px;
    margin-bottom: 40px;
}

label[for=name], 
label[for=email],
label[for=number],
label[for=dropdown],
label[for=comment] {
  margin-bottom: 10px;
  display: inline-block;
}

#video-length, 
#content-quality,
#more-videos,
fieldset input {
  height: 20px;
  width: 20px;
  margin-right: 15px;
  margin-bottom: 15px;
}

#comment {
  min-height: 180px;
}

label[for=comment]{
  margin-top: 30px
}

#submit {
  display: block;
  width: 100%;
  padding: 0.75rem;
  background: #37af65;
  border-radius: 2px;
  cursor: pointer;
  border: 0;
  color: #ffffff;
  font-size: 20px;
}

```