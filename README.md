# Ex09 Event Registration Web Application
## Date: 24/12/2025
## Ref: 25013019

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
~~~
Home Page
---------

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tech Nova</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="home">

  <header class="college-header">
    <img src="images/logo.png" alt="College Logo">
  </header>

  <section class="hero">
    <div class="hero-box">
      <h1>Tech Nova</h1>
    </div>

    <a href="register.html" class="btn">Register</a>
    <a href="events.html" class="btn">Details</a>
  </section>

</body>
</html>


.home {
  height: 100vh;
  background: linear-gradient(#8fffd3, #2fd1a4);
  text-align: center;
}

.college-header img {
  width: 90%;
  margin-top: 10px;
}

.hero {
  margin-top: 60px;
}

.hero-box {
  background: #002b36;
  color: white;
  padding: 30px;
  border-radius: 40px;
  margin: 20px;
}

.btn {
  display: block;
  width: 200px;
  margin: 15px auto;
  padding: 12px;
  background: #c8f0f0;
  color: #000;
  text-decoration: none;
  border-radius: 10px;
  font-weight: bold;
}


Events Page
-----------

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Events | Tech Nova</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="events">

  <h1 class="page-title">EVENTS</h1>

  <ul class="event-list">
    <li>⭐ Build-a-Bot</li>
    <li>⭐ Pixel Play</li>
    <li>⭐ Debug Dominion</li>
    <li>⭐ InnoQuest</li>
    <li>⭐ App Sprint</li>
  </ul>

</body>
</html>


.events {
  min-height: 100vh;
  background: linear-gradient(#ff9ad5, #ff6fae);
  padding: 30px;
}

.page-title {
  text-align: center;
  margin-bottom: 30px;
}

.event-list li {
  font-size: 20px;
  margin: 15px;
}


Registration Page
-----------------

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Registration | Tech Nova</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="register">

  <h1>Registration</h1>

  <form class="register-form">
    <input type="text" placeholder="Full Name" required>
    <input type="text" placeholder="Register Number" required>
    <input type="text" placeholder="Department" required>
    <input type="text" placeholder="Year of Study" required>
    <input type="text" placeholder="Events to Register" required>
    <input type="email" placeholder="Email" required>
    <input type="tel" placeholder="Contact Number" required>

    <button type="submit">Submit</button>
  </form>

</body>
</html>

.register {
  min-height: 100vh;
  background: #1e1e1e;
  color: white;
  padding: 20px;
}

.register-form input {
  width: 100%;
  margin: 10px 0;
  padding: 12px;
  border-radius: 6px;
  border: none;
}

.register-form button {
  width: 100%;
  padding: 12px;
  background: #69ffd2;
  border: none;
  border-radius: 8px;
  font-size: 18px;
}


Thank you Page
--------------

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Thank You | Tech Nova</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="thankyou">

  <div class="thank-card">
    <h1>Thank You!</h1>
    <p>You’re officially part of <b>Tech Nova</b> 🚀</p>

    <p class="info">
      Check your email for confirmation<br>
      Follow us on Instagram for updates<br>
      Bring your college ID on event day
    </p>
  </div>

</body>
</html>


.thankyou {
  min-height: 100vh;
  background: linear-gradient(#a66cff, #7b3fe4);
  display: flex;
  justify-content: center;
  align-items: center;
}

.thank-card {
  background: rgba(255,255,255,0.15);
  padding: 30px;
  border-radius: 20px;
  text-align: center;
  color: white;
}

.info {
  margin-top: 15px;
  line-height: 1.6;
}

~~~

## OUTPUT:

![alt text](<Screenshot 2025-12-24 090018.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
