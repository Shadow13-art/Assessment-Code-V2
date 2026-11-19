# Assessment-Code-V2
Second Version Of Assessment Code.



INDEX/HOME:

<!DOCTYPE html>
<html lang="en">
<head>
  <title>About Us</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://w3schools.com">
  <style>
    /* This puts my text on the left while my picture will be on the right. */
.bottom-split {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 32px;
  margin-top: 32px;
  margin-bottom: 32px;
  flex-wrap: wrap;
}

.left-text {
  flex: 1;
  min-width: 280px;
}

.right-img {
  width: 400px;
  max-width: 100%;
  border-radius: 8px;
}
  html, body {
  background-color: lightgrey;
  color: #3B0764;
}

    /* How to style the purple boxes. */
    .purple-box {
      background-color: rgb(110, 5, 151);
      color: #FFD700;
      border-radius: 8px;
      padding: 16px;
    }

    /* My images inside my boxes. */
    .card-img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 4px;
      display: block;
    }

    /* How to style the buttons. */
    .card-btn {
      background-color: white;
      color: rgb(110, 5, 151);
      font-weight: bold;
      padding: 10px 20px;
      margin-bottom: 16px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  
  <nav class="w3-bar w3-black">
    <a href="index.html" class="w3-button w3-bar-item">Home.</a>
    <a href="about.html" class="w3-button w3-bar-item">About Us.</a>
    <a href="contact.html" class="w3-button w3-bar-item">Contact</a>
  </nav>

  
  <div class="w3-container">
    <h1>Technology News.</h1>
    <p>Stay updated with the latest news and developments in the world of technology.</p>

   
    <div class="w3-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 16px;">
      
     
      <div class="w3-container w3-card purple-box">
        <h2>What's New in Technology?</h2>
        <img src="https://images.unsplash.com/photo-1757466762489-52fea38071ad?w=500&auto=format&fit=crop&q=60" alt="Artificial Intelligence" class="card-img">
        <p>Learn about the latest innovations and trends in technology.</p>
        <a href="ai-news.html" class="w3-button card-btn">Explore</a>
      </div>

      
      <div class="w3-container w3-card purple-box">
        <h2>Technology in Jobs</h2>
        <img src="https://plus.unsplash.com/premium_photo-1661443822504-0e382dbc1e48?q=80&w=1011&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="Technology in Jobs" class="card-img">
        <p>How can Technology be used in art, food, and architecture?</p>
        <a href="Jobs.html" class="w3-button card-btn">Explore</a>
      </div>

     
      <div class="w3-container w3-card purple-box">
        <h2>Too much?:</h2>
        <img src="https://plus.unsplash.com/premium_vector-1727448490518-477e95ae1ca3?q=80&w=387&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="Too much technology" class="card-img">
        <p>When does some Technology become too much Technology?</p>
        <a href="too-much.html" class="w3-button card-btn">Explore</a>
      </div>

  
    <div class="below-section">
      <h2>AI, is it as good as it seems?</h2>
<p>- Has AI really made our lives easier? Or is it just another way to complicate things? </p>
<p>- Has it finally gone too far?</p>
       <img src="https://plus.unsplash.com/premium_photo-1776761911865-1c12cc5c6933?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="Too much technology" class="card-img">
        </div>

<div class="bottom-split">
  

  <img src="https://images.unsplash.com/photo-1524661135-423995f22d0b?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="World Map" class="right-img">

</div>
        
      </div>
    </div>
</body>
</html>




ABOUT US:


<!DOCTYPE html>
<html lang="en">
<head>
  <title>About Us</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://w3schools.com">
  <style>
html, body {
  background-color: lightgrey;
  color: #3B0764;
}
    /* Styling of purple boxes. */
    .purple-box {
      background-color: rgb(110, 5, 151);
      color: #FFD700;
      border-radius: 8px;
      padding: 16px;
      display: flex;
      flex-direction: column;
    }
    html {
      background-color: lightgrey;
    }

    /* again*/
    .purple-box {
      background-color: rgb(110, 5, 151);
      color: #FFD700;
      border-radius: 8px;
      padding: 16px;
      display: flex;
      flex-direction: column;
    }

    /* Image sizing */
    .card-img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 4px;
      display: block;
    }

    /* Button styles */
    .card-btn {
      background-color: white;
      color: rgb(110, 5, 151);
      font-weight: bold;
      padding: 10px 20px;
      margin-top: auto;
      margin-bottom: 16px;
      border-radius: 4px;
      align-self: flex-start;
    }

    /* New section below  */
    .below-section {
      margin-top: 32px;
      margin-bottom: 32px;
    }

    .side-by-side {
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .side-img {
      width: 300px;
      max-width: 100%;
      border-radius: 8px;
    }

    .side-text {
      flex: 1;
      min-width: 250px;
    }
  </style>
</head>
<body>


  <nav class="w3-bar w3-black">
    <a href="index.html" class="w3-button w3-bar-item">Home.</a>
    <a href="about.html" class="w3-button w3-bar-item">About Us.</a>
    <a href="contact.html" class="w3-button w3-bar-item">Contact</a>
  </nav>

  
  <div class="w3-container">
    <h1>About Us.</h1>
    <p>Learn more about our company and what we do!</p>

    
    <div class="w3-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 16px;">
      
      
      <div class="w3-container w3-card purple-box">
        <h2>Who we are:</h2>
       <img src="https://plus.unsplash.com/premium_photo-1681487746049-c39357159f69?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="Lock" class="card-img">
        <p>Learn about who we are and what we do as a Technology News Website.</p>
        <a href="ai-news.html" class="w3-button card-btn">Explore</a>
      </div>

      
      <div class="w3-container w3-card purple-box">
        <h2>Our Services:</h2>
                <img src="https://plus.unsplash.com/premium_photo-1669658981858-b2ae0d7581a3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="our services" class="card-img">
        <p>Learn about the range of services that we provide for your benefit!</p>
        <a href="Jobs.html" class="w3-button card-btn">Explore</a>
      </div>

      
      <div class="w3-container w3-card purple-box">
        <h2>Why Choose Us?:</h2>
        <img src="https://images.unsplash.com/photo-1620802421041-cfb402036374?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="why choose us" class="card-img">
        <p>Learn why you should trust us with your technology news.</p>
        <a href="too-much.html" class="w3-button card-btn">Explore</a>
      </div>

    </div> <!-- End of Purple Boxes Grid -->

    
    <div class="below-section">
      <h2>Want to Understand More?</h2>
      <div class="side-by-side">
       <img src="https://plus.unsplash.com/premium_photo-1789808013975-51278a5f6199?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D" alt="Your image description" class="side-img">
        <div class="side-text">
          <p>Looking at the links above will allow you to gain a full understanding of what it is we do and what our aims are as a website! Learn all about who we are, what we do and why we are the best option for you.</p>
        </div>
      </div>
    </div>

  </div>
 
    <div class="below-section">
      <h2>Concerns</h2>
<p>Have a question or concern? Type it below and send it to us:</p>

<form action="#" method="post">
  <textarea class="concern-box" name="concerns" rows="5" placeholder="Type your concerns here:"></textarea>
  <br>
  <button type="submit" class="w3-button submit-btn">Submit</button>
</form>
          
        </div>
      </div>
    </div>
</body>
</html>
