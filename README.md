
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
	<header><h1 align="center"><u>Happy Birthday My Only One Angel</u></h1></header>
	<nav><a href="Htets.m4a">For Gift Song</a> </nav>
<script language="javascript">
alert("Welcome Lovely and cherished Htettt")
</script>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Happy Birthday</title>
<style>
h1{color:#0FF;font-family:"Arial Black", Gadget, sans-serif;font-style:italic;font-size:20px;}
body{background:url(../Users/zayar/OneDrive/Documents/Unnamed%20Site%202/happy-birthday-flowers-1536x1024.jpg); background-attachment:fixed; background-size:fixed;}
#g{color:#F0C; border:5px; border-style:outset; border-width:5px;}

</style>
	<style>
        /* Style for the slideshow container */
        .slideshow-container {
            max-width: 600px;
            position: relative;
            margin: left;
        }

        /* Style for each slide */+
		
        .mySlides {
            display: none;
            width: 80%;
        }

        /* Style for navigation dots */
        .dot {
            height: 15px;
            width: 15px;
            margin: 0 2px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.6s ease;
        }

        .active {
            background-color: #717171;
        }
		/* Style for heart-shaped images */
        .heart-image {
            width: 100%;
            height: auto;
            clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
        }
    </style>
</head>

<body>
<div class="slideshow-container">

    <!-- Heart-shaped slides -->
    <div class="mySlides">
        <img class="heart-image" src="2023_10_31_19_25_IMG_0437.JPG" alt="Heart 1">
  </div>

    <div class="mySlides">
        <img class="heart-image" src="2023_10_31_19_25_IMG_0437.JPG" alt="Heart 2">
    </div>

    <div class="mySlides">
        <img class="heart-image" src="2023_11_26_20_58_IMG_0734.JPG" alt="Heart 3">
    </div>

    <!-- Navigation dots -->
    <div style="text-align:center">
        <span class="dot"></span>
        <span class="dot"></span>
        <span class="dot"></span>
    </div>

</div>

<script>
    // JavaScript for the slideshow functionality
    let slideIndex = 0;
    showSlides();

    function showSlides() {
        let i;
        const slides = document.getElementsByClassName("mySlides");
        const dots = document.getElementsByClassName("dot");

        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }

        slideIndex++;

        if (slideIndex > slides.length) {
            slideIndex = 1;
        }

        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }

        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";

        setTimeout(showSlides, 2000); // Change slide every 2 seconds
    }
</script>
</body>
</html>
