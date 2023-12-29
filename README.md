# Ex-06-Book-Cover-Design
# AIM:
To develop a website to display the cover page design of a book
# DESIGN STEPS:
# Step 1:
Create a new Django project and app.
# Step 2:
Create a static file directory and mention the changes in settings.
# Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
# Step 4:
Write down the code for book cover using HTML and CSS.
# Step 5:
Add images and other contents using CSS record a screenshot of it.
# CODE:
<!DOCTYPE html>

    <html lang="en">
    <head>
        <title>Book Coverpage</title>
         <style>
       .bookpage
        {
            width:400px;
            height:650px;
            padding:20px;
            background-image:url("_Milky Way With Mountains Silhouette_ by Stocksy Contributor _Javier Pardina_.jpg") ;
            background-position: center;
            margin-left: 500px;
            background-repeat:no-repeat;
          }
        .h1
        {
            color:white;
        }

        .toptext
        {
            color:white;
            padding-left:5px;
            font-size: 14px;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        .tophr
        {
            color:white;
            width:225px;
        }
        hr
        {
            color:white;
        }
        .booktitle
        {
            font-family:Arial, Helvetica, sans-serif ;
            color:white;
            padding:10px 10px 0px 10px;
            display:flex;
            align-items:center;
            justify-content:center ;
            /*margin-left:10px;
            margin-right:20px;*/
            line-height:normal;
            font-size: 22px;
        }
        .author
        {
            color:white;
            display:inline;
            position:relative;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 20px;
            line-height: 5px;
        }

        .subtext
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            display:flex;
            line-height: 5px;
           /* margin-right:10px;
            margin-left:20px;*/
            font-size: 15px;
        }
        .footer
        {
            color:white;
            padding-top:180px;
        }
        .image
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 20px;
         }

        .bottomhr
        {
            color:white;
            width:400px;
        }
        img
        {
            width:90px;
            height: 100px;
            margin-right: 20px;
            vertical-align: bottom;
        }

        .edition
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 22px;
            line-height:bottom;
        }
    </style>
    </head>
   <body>
    <div class="bookpage">
        <div class="toptext">THE NEW YORK TIMES BESTSELLER</div>
        <div class="tophr"><hr></div>
        <div class="booktitle"><h1>The Universe In A Nutshell</h1></div>
        <h3 class="subtext">&nbsp;The inspiring sequel to a brief history of time</h3>
        <h3 class="subtext">&nbsp;The universe has no ultimate purpose; it simply is.</h3>
        <div class="footer">
            <h2 class="edition">&nbsp;&nbsp;First edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="sh.jpg"></h2>
            <div class="bottomhr"><hr></div>
            <div class="author"><h3>&nbsp;&nbsp;Stephen Hawking&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bantam</h3></div>
        </div>
    </div>
   </body>
    
    
</html>

# OUTPUT:
![Screenshot 2023-12-15 175545](https://github.com/23008112/Ex-06-Book-Cover-Design/assets/138972470/884cbcc5-2df8-4fe1-b5fb-c8fc75708c95)
# RESULT:
Thus a website to display the cover page design of a book was successfully created.
