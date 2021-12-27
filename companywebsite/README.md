# Web Design for a Software Product Company

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

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Navi company</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Navi company.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="products.html">Products</a></div>
        <div class="menuitem"><a href="products.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">Contact Us</a></div>
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
        Copyright &#169; 2021 Navi company, Developed by Naveenkumar.
      </div>
    </div>
  </body>
</html>
```
### products:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Navi company</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Navi company.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/acunetix.png" alt="product image">
                  </div>
                  <div class="itemname">ACUNETIX</div>
                  <div class="itemprice">Price: Rs.1000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/battlelog.png"  alt="product image">
                  </div>
                  <div class="itemname">BATTLELOG</div>
                  <div class="itemprice">Price: Rs.1500 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/brackets.png" alt="product image">
                </div>
                <div class="itemname">BRACKETS</div>
                <div class="itemprice">Price: Rs.2000 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/ethical.png" alt="product image">
              </div>
              <div class="itemname">ETHICAL HACKING</div>
              <div class="itemprice">Price: Rs.2500</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/hack.png" alt="product image">
            </div>
            <div class="itemname">HACKODE</div>
            <div class="itemprice">Price: Rs. 3000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/hashcat.png" alt="product image">
          </div>
          <div class="itemname">HASHCAT</div>
          <div class="itemprice">Price: RS.3500 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/kismet.png" alt="product image">
        </div>
        <div class="itemname">KISMET</div>
        <div class="itemprice">Price: RS.4000 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/maltego.png" alt="product image">
      </div>
      <div class="itemname">MALTEGO</div>
      <div class="itemprice">Price: Rs.4500 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/metasploit.png" alt="product image">
    </div>
    <div class="itemname">METASPLOIT</div>
    <div class="itemprice">Price: Rs.5000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/nmap.png" alt="product image">
  </div>
  <div class="itemname">NMAP</div>
  <div class="itemprice">Price: Rs.5500 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/nvs.png" alt="product image">
  </div>
  <div class="itemname">NESSUS VUNERABILITY SCANNER</div>
  <div class="itemprice">Price: Rs.6000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/set.png" alt="product image">
  </div>
  <div class="itemname">SOCIAL ENGINEER TOOLKIT</div>
  <div class="itemprice">Price: Rs.6500 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Navi company, Developed by Naveenkumar.
      </div>
    </div>
  </body>
</html>
```
### people:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Navi company</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>SUPPORTERS OF OUR SOFTWARES</h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/tomholland.jpg" alt="product image">
                    </div>
                    <div class="itemname">TOMHOLLAND</div>
                    <div class="itemprice">CEO</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/tomhardy.jpg"  alt="product image">
                    </div>
                    <div class="itemname">TOMHARDY</div>
                    <div class="itemprice">CHAIRMAN</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/tomcruise.jpg"  alt="product image">
                    </div>
                    <div class="itemname">TOMCRUISE</div>
                    <div class="itemprice">BUISSINESS MAN</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/andrew.jpg"  alt="product image">
                    </div>
                    <div class="itemname">ANDREW GARFILED</div>
                    <div class="itemprice">PROFESSIONAL HACKER</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/venkatesh.jpg"  alt="product image">
                    </div>
                    <div class="itemname">VENKATESH BHAT</div>
                    <div class="itemprice">ETHICAL HACKER</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/tony.jpg"  alt="product image">
                    </div>
                    <div class="itemname">TONY STARK</div>
                    <div class="itemprice">WHITE COLAR HACKER</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Navi company, Developed by Naveenkumar.
      </div>
    </div>
  </body>
</html>
```
### contactus:

```
<!DOCTYPE html>
<html lang="en">   
  <head>
    <title>Navi company</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Navi company</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address: Navi jigarthanda company,KANCHIPURAM <br></li>
              <li>Contact:123456787;<br></li>
              <li>E-mail:naveeen2003@gmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 Navi company, Developed by Naveenkumar.
      </div>
    </div>
  </body>
</html>
```


## OUTPUT:

### Home Page:
![output](./static/img/img1.png)
### Product Page:
![output](./static/img/img2.png)
### People Page:
![output](./static/img/img.3.png)
### Contactus Page:
![output](./static/img/img4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
