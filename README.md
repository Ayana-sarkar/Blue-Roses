# Blue-Roses
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Webpage</title>
  <style>
    body {
      background-image: url("Rosasbg.jpg");
      background-size: cover;
      background-position: centre;
      background-repeat: no-repeat;
      background-attachment: fixed;
      margin: 0;
      font-family: sans-serif;
    }
  .square-card {
  width: 180px;           /* Sets the box width */
  height: 180px;          /* Sets the box height equal to width for a square */
  float: left;            /* Moves the box to the left margin */
  margin-right: 20px;     /* Adds breathing room between the box and your text */
  overflow: hidden;       /* Crops anything outside the square boundaries */
  border-radius: 6px;     /* Optional: rounds the corners of the box */
}
/* Forces the image to fill the square box cleanly */
.square-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;      /* Preserves aspect ratio while filling the square */
}
    .animated-card {
      opacity:0 ;
    transfrom:translateY(30px);
    animation:slideUpFade 1.2s ease-out forwards ;
    }
    @keyframes slideUpFade {
    from{
    opacity: 0;
      transfrom:translateY(30px);}
      to{
      opacity: 1;
        transfrom:translateY(0);}
        }
    .animated-card h3 {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Changes font style */
  font-size: 24px;         /* Increases/decreases heading size */
  font-weight: 700;        /* Sets boldness (400 is normal, 700 is bold) */
  color: #333333;          /* Sets text color */
  margin-bottom: 8px;      /* Spacing below the title */
  line-height: 1.2;
}
/* Style the Paragraph text inside the animated card */
.animated-card p {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: 15px;         /* Base text size */
  font-weight: 400;        /* Normal weight */
  color: #555555;          /* Slightly lighter gray for body text */
  line-height: 1.6;        /* Increases vertical space between wrapped lines */
  margin: 0;               /* Removes default browser paragraph margins */
}
        btn {
        display: inline-block;
        background: linear-gradient(135deg, var(--accent-yellow), #ea580c);
        color: black;
        padding: 0.8rem 2rem;
        border-radius: 5px;
        text-decoration: none;
        font-weight: bold;
        transition: transform 0.3s, box-shadow 0.3s;
    }
      



    
    </style>
    <body>
<div class="square-card">
    <img src="Rosas.jpg" align="left" width="150" style="margin-right:20px ;"  alt= "Descrpition">
</div>
   <div class="animated-card"> 
   <p>aaaaadkdfjoifjiushffff </p>
   </div>
   <footer>
        <a href="https://ayana-sarkar.github.io/1st_rough_jjk/" class="btn" > ingredients </a>
    </footer>
</body>
</html>
