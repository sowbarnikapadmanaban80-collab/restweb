# Ex.06 Restaurant Website
## Date:19/12/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background:url(bg\ image.png) no-repeat center/cover;
    width: 100%;  

}
.name{
    font-size: 30px;
    font-weight: bold;
    position: absolute;
    left: 5%;
    margin-top: 90px;
    
      
}
.menu{
    position: absolute;
    left: 75%;
    margin-top: 160px;
    font-size: 18px;
    display: flex;
    gap: 20px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}

.footer{
    margin-top: 790px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.pic
{
    width: 1500px;
    height: 550px;
    margin-top: 120px;
    background: url(bg\ image.png) no-repeat center/cover;
    position: absolute;
}
.pic {
    display: flex;
    justify-content: center;
    gap: 60px;
    margin-top: 250px;
}

.pic img {
    width: 500px;        
    height: 500px;      
    border-radius: 10px;
}

.txt{
     color: white;
     font-size: 32px;
     position: absolute;
     left: 5%;
     margin-top: 150px;
    -webkit-text-stroke: 2px black;
}


<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet"  href="style.css">
    </head>
    <body>
        <div class="container">
           
                
                 <div class="name">
                    Copper And Ember Restaurant
                 </div>
                </div>
                <div class="Menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="txt">
                Taste the divine...
                </div>
            <div class="pic">
                 
            </div>
            <div class="footer">
                <footer>&copy; SOWBARNIKA M P(25015490)</footer>
            </div>
        </div>
    </body>
</html>

body{
     background-color: peachpuff;
     height: 3px;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background:url(bg\ image.png) no-repeat center/cover;
    width: 100%;  
    gap: 20px; 
    align-items: center; 
}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
    position: absolute;
    top: 7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 30px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}

.item{
       margin-top: 25px;
       margin-bottom: 25px;
       width: 220px;     
       background-color: cyan;     
       border: 1px solid red;    
       padding: 3px;     
       box-sizing: border-box;     
       border-radius: 8px;     
       box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
       text-align: center;  
       margin-left: 115px;
}
h3{
    font-size: 16px;
}
.price{
    font-size: 14px;
}
img{
    height: 145px;
    width: 130px;
    border-radius: 8px;

}

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet"  href="style 2.css">
    </head>
    <body>
       <h1>Our Menu</h1><br>
            <div class="Menu">
                    
                 <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
            <div class="container">
            <div class="item">
                <img src="spaghetti.png" alt="Spaghetti">         
                <h3>Spaghetti</h3>         
                <p class="price">Rs.200</p>          
            </div>
             <div class="item">
                <img src="bruschetta.png" alt="Bruschetta">         
                <h3>Bruschetta</h3>         
                <p class="price">Rs.350</p>         
                
</div>
             <div class="item">
                <img src="pepperoni pizza.png" alt="Pepperoni pizza">         
                <h3>Pepperoni pizza</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
            <div class="item">
                <img src="quesadillas.png" alt="Quesadillas">         
                <h3>Quesadillas</h3>         
                <p class="price">Rs.190</p>         
                
            </div>
            <div class="item">
                <img src="osso buco.png" alt="Osso Buco">         
                <h3>Osso Buco</h3>         
                <p class="price">Rs.320</p>         
                
            </div>
            <div class="item">
                <img src="apple pie dessert.png" alt="Apple Pie Dessert">         
                <h3>Apple Pie Dessert</h3>         
                <p class="price">Rs.200</p>         
                
            </div>
            <div class="item">
                <img src="pancakes with maple syrup.png" alt="Pancakes with maple syrup">         
                <h3>Pancakes with maple syrup</h3>         
                <p class="price">Rs.270</p>         
                
            </div>
            <div class="item">
                <img src="coleslaw.png" alt="Coleslaw">         
                <h3>Coleslaw</h3>         
                <p class="price">Rs.140</p>         
                
              </div>
           </div>
         </div>
    </div>
           
    <div class="footer">
                <footer>&copy; SOWBARNIKA M P(25015490)</footer>
            </div>
    </body>
</html>

body{
     background-color: peachpuff;
     height: 5px;
     margin: 0;
}
.container{
     display:flex;
     flex-wrap: wrap;
     background:url(bg\ image.png) no-repeat center/cover;
     width: 100%;  
     gap: 20px; 
     align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
    position: absolute;
    top:7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 650px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}

.admin{
    margin-top: 185px;
    margin-bottom: 190px;
    width: 230px;     
    background-color: cyan;     
    border: 1px solid red;    
    padding: 3px;     
    box-sizing: border-box;     
    border-radius: 8px;     
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
    text-align: center;   
}
h3{
    font-size: 20px;
}

img{
    height: 220px;
    width:175px;
    border-radius: 8px;
}


<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet"  href="style 3.css">
    </head>
    <body>
       
       <h1>Administration</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="admin">
                <img src="my image.jpg" alt="CEO">
                <h4>SOWBARNIKA M P</h4>         
                <h3>CEO</h3>         
                  
                
            </div>
             <div class="admin">
                <img src="kasama.jpg" alt="Generalmanager"> 
                <h4>KASAMA</h4>        
                <h3> General Manager</h3>         
                      
                
            </div>
             <div class="admin">
                <img src="hattori.jpg" alt="HeadChef"> 
                <h4>HATTORI</h4>        
                <h3>Head Chef</h3>         
                         
                
            </div>
            <div class="admin">
                <img src="shinchan.jpg" alt="Accountslead">   
                <h4>SHINCHAN</h4>      
                <h3>Accounts Lead</h3>         
                       
                
            </div>
            <div class="admin">
                <img src="buji.jpg" alt="Marketingmanager"> 
                <h4>BUJI</h4>        
                <h3>Marketing Manager</h3>         
                        
                
            </div>
            <div class="admin">
                <img src="patlu.jpg" alt="SupplyChain">
                <h4>PATLU</h4>
                <h3>Supply Chain</h3>


            </div>
             <div class="footer">
                <footer>&copy; SOWBARNIKA M P(25015490)</footer>
            </div>
        </div>
        </body>
        </html>


body{
     background:url(bg\ image.png) no-repeat center/cover;
     height: 5px;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
    color: white;
}
.menu{
    position: absolute;
    top: 7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: rgb(242, 236, 236);
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 1275px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.address{
    text-align: center;
    position: absolute;
    left: 40%;
    margin-top: 500px;
    font-size: 20px;
    width: 300px; 
    color: white;  

}

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet"  href="style 4.css">
    </head>
    <body>
       
       <h1>Contact Us</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="container">
                <div class="address">
                    <h2>Contact Us</h2><br>
                    Visit us at:<br>
                    123 Angel Street, Heaven land, India.<br>
                    Phone:7578495043<br>
                    Email: copperandember@gmail.com
                </div>
                 <div class="footer">
                <footer>&copy; SOWBARNIKA M P(25015490)</footer>
            </div>
            </div>
            </body>
            </html>

```


## OUTPUT:

![alt text](<Screenshot 2025-12-19 203601.png>)
![alt text](<Screenshot 2025-12-19 203621.png>)
![alt text](<Screenshot 2025-12-19 203641.png>)
![alt text](<Screenshot 2025-12-19 203704.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
