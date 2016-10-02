# Topcoder Pages deconstructed

Taking Topcoder Front Page as design inspiration and converting it into code to practice my Front-end development skill.

Find Demo [here](https://abhishekraj007.github.io/apps/topcoder)


## How To

Let's see the code and approaches I followed to replicate similar design as Topcodes pages:

First thing first, Navigation top menu. I am using bootstrap to make life little easy.

```
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
    
```
After writing above markup our navigation will look like this:

![nav1](/screenshots/nav1.png)

CSS code to make our navigation look similar to topcoder navigation

```
.navbar-default {
    background-color: $white;
    height: 80px;
    border-top: 1px solid $main;
    .container-fluid {
        margin-top: 15px;
        width: 95%;
        .navbar-right {
            padding: 6px;
            a {
                margin-left: 1em;
                text-transform: uppercase;
            }
        }
    }
}
// Making default-btn style global so that it could be use anywhere on the page
.btn-default {
    background-color: $main;
    border-color: $main;
    color: $white;
    border-radius: 2px;
    font-size: 1.2em;
    padding-left: 1.2em;
    padding-right: 1.2em;
    font-weight: 600;
    text-transform: uppercase;
    &:hover {
        background-color: $blue-dark;
        border-color: $blue-dark;
        color: $white;
    }
}

```
Now our navigation will look something like this:

![styled navigation bar](screenshots/nav2.png)

## Note

ALL of the contents and design used during practice session is the property of topcoder. I don't claim to hold any of the contents/resources. I have used the contents just for the placeholder and design as an inspiration to practice my front-end development skill.
