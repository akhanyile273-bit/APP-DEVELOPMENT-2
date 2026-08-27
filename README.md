# APP-DEVELOPMENT-2
My App Development 2 project is about Safe Lens, a feature that safeguards social media users when they share content over social media. It is demonstrated in the form of a website
# STARTED OFF MY WEBSITE WITH HTML, ADDING ALL THE CONTENT, & NAV LINKS THE WEBSITE WILL REQUIRE
# INDEX
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="safe-lens-logo.png">
    <title>Safe Lens - Your Digital Security Guard</title>

    <!-- Google Fonts: Poppins for headings, Roboto for body text -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700;800&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

    <!-- Our stylesheet -->
    <link rel="stylesheet" type="text/css" href="index.css" />
</head>
<body>

    <header class="safe-lens-header">
        <div class="logo-container">
            <a href="index.html" class="logo">
                <img src="safe-lens-logo.png" width="48" height="48" alt="Safe Lens logo">
                <span class="logo-text">Safe<span class="logo-accent">Lens</span></span>
            </a>

            <!-- Hamburger button: only visible on small screens, controlled by index.js -->
            <button class="nav-toggle" id="navToggle" aria-label="Open menu" aria-expanded="false">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <nav class="navigation" id="primaryNav">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="How it Works.html">HOW IT WORKS</a></li>
                    <li><a href="demo.html">DEMO</a></li>
                    <li><a href="faq.html">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <!-- This empty div gets filled with floating emoji by index.js -->
            <div class="floaters" id="floaters" aria-hidden="true"></div>

            <h1 class="hero-title">Safe Lens <br>Your Social Media Digital Security Guard!</h1>

            <div class="intro">
                <p>
                    Social media has become a phenomenon that makes it less difficult to "love
                    thy neighbour" or to "keep your enemies closer," because these individuals are now right in the
                    palm of our hands.
                </p>

                <p>
                    It is safe to say that the many social media platforms we are exposed to
                    were created with good intention, but the use of them has become malicious especially when
                    it comes to what we share online. This is where Safe Lens comes in.
                </p>
            </div>
        </section>
    </main>

    <!-- Our JavaScript file, loaded at the end so the page content exists first -->
    <script src="index.js"></script>
</body>
</html>

# how-it-works
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="safe-lens-logo.png">
    <title>Safe Lens - How it works</title>

    <!-- Google Fonts: Poppins for headings, Roboto for body text -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700;800&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

    <!-- Our stylesheet -->
    <link rel="stylesheet" type="text/css" href="how-it-works.css" />
</head>
<body>

    <header class="safe-lens-header">
        <div class="logo-container">
            <a href="index.html" class="logo">
                <img src="safe-lens-logo.png" width="48" height="48" alt="Safe Lens logo">
                <span class="logo-text">Safe<span class="logo-accent">Lens</span></span>
            </a>

            <!-- Hamburger button: only visible on small screens, controlled by index.js -->
            <button class="nav-toggle" id="navToggle" aria-label="Open menu" aria-expanded="false">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <nav class="navigation" id="primaryNav">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="How it Works.html">HOW IT WORKS</a></li>
                    <li><a href="demo.html">DEMO</a></li>
                    <li><a href="faq.html">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <!-- This empty div gets filled with floating emoji by how-it-works.js -->
            <div class="floaters" id="floaters" aria-hidden="true"></div>

            <h1 class="hero-title">Safe Lens - <br>Think Before You Share</h1>

            <div class="intro">
                <p>
                    Social Media users put little to no thought into what they share online. Safe Lense is there to guide users
                    into a "think before you share" habit. 
                </p>

                <p>
                     Safe Lense is a camera feature that will ideally be integrated into all social media platform cameras and the 
                     default camera of all cellphone devices.  
                </p>

                <p>
                    Before the selected content is shared on the desired platform is sent or 
                    posted on the desired social media platform, the following alert will appear: <br>
                    "The selected content appears to be sensitive/explicit. <br> Think before you share.
                    Sharing content of this nature can affect your privacy, safety and future.
                    if someone else is included in this content, make sure you have their consent before Sharing. <br>
                    <b>Are you sure you want to share?"</b>
                    <br>
                    They will have the option to go back or continue.
                    Depending on the user's choice, the social media platform will return to its landing page
                    or their open chats if they select "Go back" or it will proceed to share if they select "Yes, continue".
                    This way, no matter what the user decides to do after, they will be making an informed decision.
                </p>
            </div>
        </section>
    </main>

    <!-- Our JavaScript file, loaded at the end so the page content exists first -->
    <script src="how-it-works.js"></script>
</body>
</html>

#Demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="safe-lens-logo.png">
    <title>Safe Lens - Your Digital Security Guard</title>

    <!-- Google Fonts: Poppins for headings, Roboto for body text -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700;800&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

    <!-- Our stylesheet -->
    <link rel="stylesheet" type="text/css" href="Demo.css" />
</head>
<body>

    <header class="safe-lens-header">
        <div class="logo-container">
            <a href="index.html" class="logo">
                <img src="safe-lens-logo.png" width="48" height="48" alt="Safe Lens logo">
                <span class="logo-text">Safe<span class="logo-accent">Lens</span></span>
            </a>

            <!-- Hamburger button: only visible on small screens, controlled by Demo.js -->
            <button class="nav-toggle" id="navToggle" aria-label="Open menu" aria-expanded="false">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <nav class="navigation" id="primaryNav">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="How it Works.html">HOW IT WORKS</a></li>
                    <li><a href="demo.html">DEMO</a></li>
                    <li><a href="faq.html">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="row">
    <div class="column">
    <img src="INSTAGRAM DEMO.png" alt="Instagram Demo" style="width:300px;height:500px;" class ="center">
  </div>
  <div class="column">
    <img src="WA DEMO.png" alt="Whatsapp Demo" style="width:300px;height:500px;" class ="center">
  </div>

    <main>
        <section class="hero">
            <!-- This empty div gets filled with floating emoji by index.js -->
            <div class="floaters" id="floaters" aria-hidden="true"></div>

            <h1 class="hero-title">Safe Lens <br>In-Real-Life Demo</h1>
            <p>
                These images demostrate the feature in live action for Instagram and for Whatsapp.
            </p>

    <!-- Our JavaScript file, loaded at the end so the page content exists first -->
    <script src="Demo.js"></script>

    #faq
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="safe-lens-logo.png">
    <title>Safe Lens - FAQ</title>

    <!-- Google Fonts: Poppins for headings, Roboto for body text -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;700;800&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

    <!-- Our stylesheet -->
    <link rel="stylesheet" type="text/css" href="faq.css" />
</head>
<body>

    <header class="safe-lens-header">
        <div class="logo-container">
            <a href="faq.html" class="logo">
                <img src="safe-lens-logo.png" width="48" height="48" alt="Safe Lens logo">
                <span class="logo-text">Safe<span class="logo-accent">Lens</span></span>
            </a>

            <!-- Hamburger button: only visible on small screens, controlled by faq.js -->
            <button class="nav-toggle" id="navToggle" aria-label="Open menu" aria-expanded="false">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <nav class="navigation" id="primaryNav">
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="How it Works.html">HOW IT WORKS</a></li>
                    <li><a href="demo.html">DEMO</a></li>
                    <li><a href="faq.html">FAQ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="hero">
            <!-- This empty div gets filled with floating emoji by index.js -->
            <div class="floaters" id="floaters" aria-hidden="true"></div>

            <h1 class="hero-title">Safe Lense - <br>FAQ</h1>

            <b>
                How does Safe Lense Detect Inappropriate Content?
            </b>
            <p>
                Safe Lens detects inappropriate content through Artificial Intelligance. It will compare
                content to the examples it has been taught, tailor made for the feature. The alert will
                then be triggered if it detects as taught.
            </p>
    <br>
    <b>
        Does Safe Lense automatically delete my pictures?
    </b>
    <p>
        No. <br>Safe Lense does not delete your pictures, it will only detect their explicity before you
        choose to share it on social media or not. You will stil be able to access them in your gallery.
    </p>
    <br>
    <b>
        Can I turn Safe Lense off?
    </b>
    <p>
        You cannot turn Safe Lense off. <br>You can respond to the alert message by either going back or continuing 
        to share.
    </p>
    <br>
    <b>
        Does Safe Lense replace parental controls?
    </b>
    <p>
        Safe Lense does not replace parental controls but supports it on the go. <br>It has the same functionallity that
        parental guidance apps like Bark has. Should children choose to continue, the parent will be notified of the risk
        that arises.
    </p>
    <br>
    <b>
        What is the future of Safe Lense?
    </b>
    <p>
        At the moment, Safe lense is only detecting the explicity of images. In the near future, we plan to integrate in for 
        video detection as well, because believe it or not, people still take fottage of what sould remain private.
    </p>
            </div>
        </section>
    </main>

    <!-- Our JavaScript file, loaded at the end so the page content exists first -->
    <script src="faq.js"></script>
</body>
</html>

