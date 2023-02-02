<head>
    <meta charset="UTF-8">
    <title>Technology Website</title>
    <link rel="stylesheet" type="text/css" href="original style.css"> 
	  
  </head>
  <body style="background-image: url('image.jpg'); background-size: cover;">
    <header>
      <h1>YEAR 13 BOARD</h1>
      <nav>
        <ul>
          <li><a href="#" id="Gender gap">Gender gap</a></li>
          <li><a href="#" id="Evidence">Evidence</a></li>
          <li><a href="#" id="contactUs">Contact Us</a></li>
        </ul>
      </nav>
    </header>

    <main>
		 <h1 style="font-family:Cambria, 'Times New Roman', serif; font-size:45pt;"><b>Welcome To Our Board</b></h1>
      <p style="color: #EBEBEB">Move ahead of stereotypical gender binaries. Build a society that gives an equal opportunity to all</p>
    </main>

    <script>
      console.log("Technology Website");
      
      // Add event listeners to the buttons
      document.getElementById("Gender gap").addEventListener("click", function() {
        console.log("Gender gap button clicked");
		  window.location.href = "gendergap.html";
        // Add code here to navigate to the home page
      });
      document.getElementById("Evidence").addEventListener("click", function() {
        console.log("Articles button clicked");
        // Add code here to navigate to the articles page
      });
      document.getElementById("contactUs").addEventListener("click", function() {
        console.log("Contact Us button clicked");
        // Add code here to navigate to the contact us page
      });
    </script>
  </body>
</html>
