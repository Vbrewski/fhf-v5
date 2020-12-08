---
layout: "page"
---
<style>
.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  -webkit-transition-duration: 0.4s; /* Safari */
  transition-duration: 0.4s;
}

.button2:hover {
  box-shadow: 0 12px 16px 0 rgba(0,0,0,0.24),0 17px 50px 0 rgba(0,0,0,0.19);
}
</style>

<body style="background-color:#f8a689;"> </body>
<link href="/css/donation.css" rel="stylesheet">
<form action="https://www.gofundme.com/f/food4highlandfamilies/donate" method="get" id="form1"></form>
<html>
<head>
    <title>Title of the document</title>
</head>
<div class="Banner">
    <img src="/assets/img/helpus.jpg"><br>
    <div class="banner-text">Help a Family in need.</div>
</div>
<body>
<h1>Your Donations Make a Difference</h1><br>
<div class="container">
    <button class="button button2" type="submit" form="form1" formtarget="_blank" id="1">
        <h2>$5</h2>
        <p> Buy 1 meal for a family in need. </p>
    </button>
    <button class="button button2" type="submit" form="form1" formtarget="_blank" id="2">
        <h2>$15</h2>
        <p>Buy 3 meal for a family in need. </p>
    </button>
    <button class="button button2" type="submit" form="form1" formtarget="_blank" id="3">
        <h2>$25</h2>
        <p>Buy 5 meal for a family in need. </p>
    </button>
    <button class="button button2" type="submit" form="form1" formtarget="_blank" id="4">
        <h2>$50</h2>
        <p>Buy 10 meal for a family in need. </p>
    </button>
    <br>
    <button class="button button2" type="submit" form="form1" formtarget="_blank" id="5">
        <h2>Custom Amount</h2>
    </button>
</div>
</body>
</html>