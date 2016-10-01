# Topcoder Pages deconstructed

Taking Topcoder Front Page as design inspiration and converting it into code to practice my Front-end development skill.

Find Demo [here](https://abhishekraj007.github.io/apps/topcoder)


## Steps followed

Let's see how I approached to deconstruct this page. I will be using bootsrap to make life easy.

First thing first, The Navigation Menu.

HTML Code for navigation menu:

---
    <!-- ------------------------------------------------
        -------------- HEADER NAV SECTION-------------- -->
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
---

CSS code for nav menu:


---
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

---







##Note

ALL of the contents and design used during practice session is the property of topcoder. I don't claim to hold any of the contents/resources. I have used the contents just for the placeholder and design as an inspiration to practice my front-end development skill.
