# Topcoder Pages deconstructed

Taking Topcoder Front Page as a design inspiration and converting it into code to practice Front-end development skill.

[Demo](https://abhishekraj007.github.io/apps/topcoder)


## How To

Let's see the code and approaches involved to replicate the similar design that you see on the front page of Topcoder website:

##### Table of contents    
   
* [Navigation Menu](#navigation)
* [Section 1](#section1)
* [Section 2](#section2)  
* [Section 3](#section3)  
* [Section 4](#section4)

<a name="navigation">
## Top Navigation Menu
First thing first, Build Top menu (Using bootstrap to make life little easy).

```html
<!--  Top Navigation Bar -->
    <header>
        <nav class="navbar navbar-default navbar-fixed-top">
            <div class="container-fluid">
                <div class="navbar-header">
                    <!-- Menu Button for small devices -->
                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#nav-menu" aria-expanded="false">
                        <span class="sr-only">Navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                      </button>
                      <!-- Logo -->
                    <a class="navbar-brand" href="#">top<strong>coder</strong></a>
                </div>
                <!-- navbar-header -->
                <!-- Links in right side-->
                <div class="collapse navbar-collapse" id="nav-menu">
                    <ul class="nav navbar-nav navbar-right">
                        <a href="#" class="btn btn-default">Contact Us</a>
                        <a href="#" class="btn btn-default">Log in</a>
                    </ul>
                </div>
                <!-- /.navbar-collapse -->
            </div>
            <!-- /.container-fluid -->
        </nav>
        <!-- Nav -->
    </header>
    
```
(Read bootstrap documentation here, how to create a [navigation bar](http://getbootstrap.com/components/#navbar))

After writing above markup our navigation bar will look like this:

![nav1](https://github.com/abhishekraj007/topcoder-frontend/blob/master/screenshots/nav1.PNG)

CSS code to make our navigation bar look similar to topcoder navigation

```css
.navbar-default {
  background-color: #ffffff;
  height: 80px;
  border-top: 1px solid #07a8f2;
}

.navbar-default .container-fluid {
  margin-top: 15px;
  width: 95%;
}

.navbar-default .container-fluid .navbar-right {
  padding: 6px;
}

.navbar-default .container-fluid .navbar-right a {
  margin-left: 1em;
  text-transform: uppercase;
}
// Making default button style global so that it could be use anywhere on the page
.btn-default {
  background-color: #07a8f2;
  border-color: #07a8f2;
  color: #ffffff;
  border-radius: 2px;
  font-size: 1.2em;
  padding-left: 1.2em;
  padding-right: 1.2em;
  font-weight: 600;
  text-transform: uppercase;
}

.btn-default:hover {
  background-color: #0b65a5;
  border-color: #0b65a5;
  color: #ffffff;
}

.btn-default:focus {
  background-color: #0b65a5;
  border-color: #0b65a5;
  color: #ffffff;
}

```
Now our final navigation will look something like this:

![styled navigation bar](https://github.com/abhishekraj007/topcoder-frontend/blob/master/screenshots/nav2.PNG)



<a name="section1">
## Section 1

The first section is easy, paste the following html code to generate the skeleton 

```html
    <section>
            <div class="crowd-sourcing1">
                <div class="container">
                    <div class="row">
                        <div class="col-md-7 col-xs-12">
                            <h1>Deliver faster for your business through crowdsourcing.</h1>
                            <p>With a community of over 1,000,000 design and technology experts, Topcoder provides on-demand capability, bandwidth, and velocity so you can do more.</p>
                            <div class="two-buttons">
                                <a href="#">I want to get work done</a>
                                <a href="#">I want to join Topcoder</a>
                            </div>
                            <!-- two button -->
                        </div>
                        <!-- col -->
                    </div>
                    <!-- row -->
                </div>
                <!-- container -->
            </div>
            <!-- crowd-sourcing1 -->
        </section>
        <!-- section -->

```
After writing above html markup, our code will generate view something like this:

![section1_1](https://github.com/abhishekraj007/topcoder-frontend/blob/master/screenshots/sec1_1.PNG)

Now paste the following CSS code to match with first section of topcoder page:

```css

.crowd-sourcing1 {
  background: url("https://wwwtc.wpengine.com/wp-content/themes/tc2-theme/appirio-50-50/i/desktop/bg-deliver-crowdsourcing.jpg");
  background-size: cover;
  color: #ffffff;
  height: 100%;
  width: 100%;
  padding-top: 50px;
}

.crowd-sourcing1 h1 {
  padding: 2em 0 0 0;
  font-size: 2.8em;
  line-height: 1.5em;
  letter-spacing: 1px;
}

.crowd-sourcing1 p {
  padding: 1em 0 1em 0;
  font-size: 1.4em;
  letter-spacing: 1px;
}

.crowd-sourcing1 .two-buttons {
  padding: 3em 0;
  margin-bottom: 3em;
  display: inline-block;
}

.crowd-sourcing1 .two-buttons a {
  border: 1px solid #ffffff;
  border-radius: 2px;
  color: #ffffff;
  text-decoration: none;
  font-size: 1.2em;
  padding: 1em 3em;
  margin: 1em 2em 0 0;
  display: inline-block;
}

.crowd-sourcing1 .two-buttons a:hover {
  background: rgba(246, 246, 246, 0.2);
}

```

The output after pasting above css code will generate view something like this:

![section1_2](https://github.com/abhishekraj007/topcoder-frontend/blob/master/screenshots/sec1_2.PNG)

<a name="section2">
## Section 2


<a name="section3">
## Section 3






## Note

ALL of the contents and design used during practice session is the property of topcoder. I don't claim to hold any of the contents/resources. I have used the contents just for the placeholder and design as an inspiration to practice my front-end development skill.
