
<!DOCTYPE html>
<html lang = "en">
    <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Page Title</title>
    </head>
    <body>
    <div class = "container">
        <div class = "card">
        
        
       
            
            <div class = "front_page">
                <img src = "https://api.sololearn.com/uploads/avatars/20277663.jpg">
                <hr id = "hh">
                <center><b id = "b"></b></center>
            </div>
            
       
            <div class = "back_page">
                <h3>Job description</h3>
                <hr>
                <center id = "skill"><i>Web design & developing  HTML  CSS  JS & REACT...</i></center>
                <div class = "f">
              <p id = "followers"> &nbsp;&nbsp;&nbsp;&nbsp;276 <br /> Followers </p>
              <p id = "following"> &nbsp;&nbsp;&nbsp;&nbsp;498 <br />Following</p>
              <p id = "projects"> &nbsp;&nbsp;&nbsp;&nbsp;10 <br />Projects</p>
                       </div>
              
               
                 </div>
         </div>
 </div>
 <script>
     var b = document.querySelector('#b');
        var text = "Click the page...";
            var textlength = text.length;
            var i = -1;
            var time = setInterval(write,280);
            function write(){
               i++;
               b.innerHTML += text.charAt(i);   
        }
     
 </script>
</body>       
</html>
