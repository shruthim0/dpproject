<img src="https://media3.giphy.com/media/l2Sq87bt4GOdAnlGo/giphy.gif?cid=790b7611b564906fbdb7c2d94754271b68e23e8e1e53e5c5&rid=giphy.gif&ct=g" width="550" height="250" />


# Book a flight with Lilikoi Air
> all flights from Lilikoi International (LIA)

## Create a user

<!-- below is what the user inputs; stored and eventually used -->
<table>
    <tr>
        <th><label for="name">Name</label></th>
        <th><label for="email">Email</label></th>
        <th><label for="password">Password</label></th>
        <th><label for="phone">Phone</label></th>
    </tr>
    <tr>
        <td><input type="text" name="name" id="name" required></td>
        <td><input type="email" name="email" id="email" placeholder="abc@xyz.org" required></td>
        <td><input type="password" name="password" id="password" required></td>
        <td><input type="tel" name="phone_num" id="phone_num"
            pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}"
            placeholder="999-999-9999"></td>
        <td ><button onclick="create_User()">Create</button></td>
    </tr>
<tr>
</tr>
</table>
<div class="box">
  <div class="clip"></div>
  <ul class="left">
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul>
  
  <ul class="right">
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul>
  
  <div class="ticket">
    <span class="airline">Postsnap</span>
    <span class="airline airlineslip">Postsnap</span>
    <span class="boarding">Boarding pass</span>
    <div class="content">
      <span class="jfk">LIA</span>
      <span class="plane"><?xml version="1.0" ?><svg clip-rule="evenodd" fill-rule="evenodd" height="60" width="60" image-rendering="optimizeQuality" shape-rendering="geometricPrecision" text-rendering="geometricPrecision" viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg"><g stroke="#222"><line fill="none" stroke-linecap="round" stroke-width="30" x1="300" x2="55" y1="390" y2="390"/><path d="M98 325c-9 10 10 16 25 6l311-156c24-17 35-25 42-50 2-15-46-11-78-7-15 1-34 10-42 16l-56 35 1-1-169-31c-14-3-24-5-37-1-10 5-18 10-27 18l122 72c4 3 5 7 1 9l-44 27-75-15c-10-2-18-4-28 0-8 4-14 9-20 15l74 63z" fill="#222" stroke-linejoin="round" stroke-width="10"/></g></svg></span>
      <span class="sfo">LAX</span>
      
      <span class="jfk jfkslip">LIA</span>
      <span class="plane planeslip"><?xml version="1.0" ?><svg clip-rule="evenodd" fill-rule="evenodd" height="50" width="50" image-rendering="optimizeQuality" shape-rendering="geometricPrecision" text-rendering="geometricPrecision" viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg"><g stroke="#222"><line fill="none" stroke-linecap="round" stroke-width="30" x1="300" x2="55" y1="390" y2="390"/><path d="M98 325c-9 10 10 16 25 6l311-156c24-17 35-25 42-50 2-15-46-11-78-7-15 1-34 10-42 16l-56 35 1-1-169-31c-14-3-24-5-37-1-10 5-18 10-27 18l122 72c4 3 5 7 1 9l-44 27-75-15c-10-2-18-4-28 0-8 4-14 9-20 15l74 63z" fill="#222" stroke-linejoin="round" stroke-width="10"/></g></svg></span>
      <span class="sfo sfoslip">LAX</span>

      <!-- below is what is written on the ticket -->
      <div class="sub-content">
      <!-- added watermark -->
        <span class="watermark">Lilikoi Air</span>
        <span class="name">PASSENGER NAME<br><span>SAVLANI, Jiya</span></span>
        <span class="flight">FLIGHT N&deg;<br><span>X3-65C3</span></span>
        <span class="gate">GATE<br><span>11B</span></span>
        <span class="seat">SEAT<br><span>45A</span></span>
        <span class="boardingtime">BOARDING TIME<br><span>8:25PM ON JANUARY 2023</span></span>
            
         <span class="flight flightslip">FLIGHT N&deg;<br><span>X3-65C3</span></span>
          <span class="seat seatslip">SEAT<br><span>45A</span></span>
         <span class="name nameslip">PASSENGER NAME<br><span>SAVLANI, Jiya</span></span>
      </div>
    </div>
  </div>
</div>



<html>
  <head>
    <meta charset="utf-8">
    <title>FAQ</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.3/css/bootstrap.min.css">
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <style type="text/css">
      body{
        background: #eee;
        padding-top: 20px;
        font-family: monospace;
      }
      .header{
        border-radius: 20px 20px 0px 0px;
        padding: 10px 0px;
        background: purple;
        color: #fff;
        width: 100%;
        display: flex;
        align-content: center;
        justify-content: center;
      }
      .faq-item{
        margin-bottom: 40px;
        margin-top: 40px;
      }
      .faq-body{
        display: none;
        margin-top: 30px;
      }
      .faq-wrapper{
        width: 75%;
        margin: 0 auto;
      }
      .faq-inner{
        padding: 30px;
        background: aliceblue;
      }
      .faq-plus{
        float: right;
        font-size: 1.4em;
        line-height: 1em;
        cursor: pointer;
      }
      hr{
        background-color: #9b9b9b;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="row">
        <div class="faq-wrapper">
          <div class="header">
            <h1>FAQs</h1>
          </div>
          <div class="faq-inner">
            <div class="faq-item">
              <h3>
                Can I pay for my checked bags online before my flight?
                <span class="faq-plus">&plus;</span>
              </h3>
              <div class="faq-body">
                Yes! You can pay for your checked bags online at least 24 hours before your flight. Another thing you can do is pay when you check in for your flight.
              </div>
            </div>
            <hr>
            <div class="faq-item">
              <h3>
                Are there service charges for sports equipment?
                <span class="faq-plus">&plus;</span>
              </h3>
              <div class="faq-body">
                Yes! Certain pieces of sports equipment have their own service charges. 
              </div>
            </div>
            <hr>
            <div class="faq-item">
              <h3>
                What if I left an item on the flight? ?
                <span class="faq-plus">&plus;</span>
              </h3>
              <div class="faq-body">
               If you left an item on the flight, don't worry. We will make every effort to return lost items back to you. Visit our main website for more information.
              </div>
            </div>
            <hr>
            <div class="faq-item">
              <h3>
               What are the limit for bags?
                <span class="faq-plus">&plus;</span>
              </h3>
              <div class="faq-body">
               You can check-in 2 bags per person and keep one cabin bag.
              </div>
            </div>
            <hr>
            <div class="faq-item">
              <h3>
               Will I get a refund if my flight is cancelled and I don't travel that day?
                <span class="faq-plus">&plus;</span>
              </h3>
              <div class="faq-body">
                You will get a refund for checked bags service charges when you involuntarily do not travel. 
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <script type="text/javascript">
      $(".faq-plus").on('click',function(){
        $(this).parent().parent().find('.faq-body').slideToggle();
      });
    </script>
  </body>
</html>


<iframe width="0" height="0" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/206903676&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
 

# How was your experience?
<textarea rows="10" cols="80">    
                          Thank you for flying with LIA! 
                           Write your experience here. 