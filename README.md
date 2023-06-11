# EX07 Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```product.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>

home.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Arun kumar.
      </div>
    </div>
  </body>
</html>

people.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMIN' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/banner1.jpg" type="image/x-icon" />
  </head>

  <body>
   <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
            <h1>Our Team</h1>
            <div class="peopleitems">
                <div class="peopleitem">
                    <div class="peopleimage">
                    <img src="./img/peo1.jpg" alt="people1 image">
                    </div>
                    <div class="peoplename">MR.Deniz</div>
                    <div class="peoplepos">MD and CEO</div>
                </div>
                <div class="peoplecontent"> 
                  <div class="peopleitems">
                      <div class="peopleitem"> 
                          <div class="peopleimage">
                          <img src="./img/peo2.jpg" alt="people2 image">
                          </div>
                          <div class="peoplename">MR.Albert</div>
                          <div class="peoplepos">CPO</div>
                      </div>
                      <div class="peoplecontent">   
                      
                        <div class="peopleitems">
                            <div class="peopleitem"> 
                                <div class="peopleimage">
                                <img src="./img/peo3.jpg" alt="people3 image">
                                </div>
                                <div class="peoplename">MS.Filiz</div>
                                <div class="peoplepos">CHRO</div>
                            </div>
                      
                        <div class="peoplecontent">  
                                
                                    <div class="peopleitems">
                                        <div class="peopleitem"> 
                                            <div class="peopleimage">
                                            <img src="./img/peo4.jpg" alt="people4 image">
                                            </div>
                                            <div class="peoplename">MR.Sylvester</div>
                                            <div class="peoplepos">Joint MD and CTO</div>
                              </div>
                        <div class="peoplecontent"> 
                                          
                                          <div class="peopleitems">
                                              <div class="peopleitem"> 
                                                  <div class="peopleimage">
                                                  <img src="./img/peo5.jpg" alt="people5 image">
                                                  </div>
                                                  <div class="peoplename">MR.William</div>
                                                  <div class="peoplepos">Head,Retail Sales</div>
                               </div>
                               <div class="peoplecontent">    
                           
                                <div class="peopleitems">
                                    <div class="peopleitem"> 
                                        <div class="peopleimage">
                                        <img src="./img/peo6.jpg" alt="people6 image">
                                        </div>
                                        <div class="peoplename">Ms.Olivia</div>
                                        <div class="peoplepos">CFO</div>
                     </div>


                
          </div>
        </div>
      <div>
      <div class="footer">
        Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by Arun kumar.
      </div>
     </div>
     </body>
</html>
 
 home.html

 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMIN' IS NOT A CRIME</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/banner1.jpg" type="image/x-icon" />
  </head>

  <body>
   <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
            <h1>Our Team</h1>
            <div class="peopleitems">
                <div class="peopleitem">
                    <div class="peopleimage">
                    <img src="./img/peo1.jpg" alt="people1 image">
                    </div>
                    <div class="peoplename">MR.Deniz</div>
                    <div class="peoplepos">MD and CEO</div>
                </div>
                <div class="peoplecontent"> 
                  <div class="peopleitems">
                      <div class="peopleitem"> 
                          <div class="peopleimage">
                          <img src="./img/peo2.jpg" alt="people2 image">
                          </div>
                          <div class="peoplename">MR.Albert</div>
                          <div class="peoplepos">CPO</div>
                      </div>
                      <div class="peoplecontent">   
                      
                        <div class="peopleitems">
                            <div class="peopleitem"> 
                                <div class="peopleimage">
                                <img src="./img/peo3.jpg" alt="people3 image">
                                </div>
                                <div class="peoplename">MS.Filiz</div>
                                <div class="peoplepos">CHRO</div>
                            </div>
                      
                        <div class="peoplecontent">  
                                
                                    <div class="peopleitems">
                                        <div class="peopleitem"> 
                                            <div class="peopleimage">
                                            <img src="./img/peo4.jpg" alt="people4 image">
                                            </div>
                                            <div class="peoplename">MR.Sylvester</div>
                                            <div class="peoplepos">Joint MD and CTO</div>
                              </div>
                        <div class="peoplecontent"> 
                                          
                                          <div class="peopleitems">
                                              <div class="peopleitem"> 
                                                  <div class="peopleimage">
                                                  <img src="./img/peo5.jpg" alt="people5 image">
                                                  </div>
                                                  <div class="peoplename">MR.William</div>
                                                  <div class="peoplepos">Head,Retail Sales</div>
                               </div>
                               <div class="peoplecontent">    
                           
                                <div class="peopleitems">
                                    <div class="peopleitem"> 
                                        <div class="peopleimage">
                                        <img src="./img/peo6.jpg" alt="people6 image">
                                        </div>
                                        <div class="peoplename">Ms.Olivia</div>
                                        <div class="peoplepos">CFO</div>
                     </div>


                
          </div>
        </div>
      <div>
      <div class="footer">
        Copyright &#169; 2023 Gamer'sworld.MGamers.org, Developed by Arun kumar.
      </div>
     </div>
     </body>
</html>
```



### Home Page:

![image](https://github.com/SudharsanamRK/productcompanywebsite/assets/115523484/16509685-5e07-4eda-97f1-218ceea2ebff)
## OUTPUT:
![image](https://github.com/SudharsanamRK/productcompanywebsite/assets/115523484/83e964ae-ccb6-44e1-8c11-d7cdfa681126)
![image](https://github.com/SudharsanamRK/productcompanywebsite/assets/115523484/627ef5a5-1eb2-485c-a184-53d0be7d88d2)
![image](https://github.com/SudharsanamRK/productcompanywebsite/assets/115523484/d7621228-df0a-4a56-9118-bf5c9ecf66ee)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
