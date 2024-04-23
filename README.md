# MuseumofCandy-
The code and description of a mock front-end Museum of Candy information page.

This page was built in my website design certification course.

For this code, I worked on creating a responsive page with four rows set up with a picture on one side and text on the other. There is a responsive and sticky menu at the top of the page, and I used stock pictures that stayed true to the design. For this page, the inspiration is a bright pink Candy Shop paired with the fun of a museum. Since this page is not accessible, I had a lot of work ahead of me to make this bright page accessible but still fun! Below are all of the changes highlighted as ** **.

HTML CODE I chose not to use alt text for the images because they are purely decorative. The message of the webpage is conveyed without the description of the images.
I also changed the HTML code to darken the text in the first row because it was too light. 

**Original HTML:**
 	<div id="headingGroup" class="text-white text-center d-none d-lg-block mt-5">

**Accessible HTML:**
	<section class="container-fluid px-0">
       		<div class="row align-items-center">
           		<div class="col-lg-6">
                		<div id="headingGroup" class="text-#51010B text-center d-none d-lg-block mt-5">
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                    			<h1 class="">MUSEUM<span>/</span>OF<span>/</span>CANDY</h1>
                		</div>
            		</div>
            	<div class="col-lg-6">
                	<img class="img-fluid" src="imgs/hand2.png" alt="">
            	</div>
        </div>
    </section>
	
Looking at the CSS Code the changes I made helped me make sure that this page is not only responsive but also accessible.

**Original CSS Code:**

	body {
   		**background: #f5d9d5;**
	}

	.blurb h2 {
  		**color: #EA1C2C;**
	}

	.blurb p {
    		**color: #f498b8;**
	}

	#mainNavbar .nav-link {
   		**color: white;**
	}

	#mainNavbar .nav-link:hover {
   		**color: #EA1C2C;**
	}

	#mainNavbar .navbar-brand {
    		**color: #EA1C2C;**
	}

	#headingGroup span {
    		**color: #EA1C2C;**
	}

	.navbar.scrolled {
    		**background: rgb(222,192,222);**
	}

The hardest part about this accessibility change was getting the color contrast correct so that the contents were dark enough to be read without taking away the fun from the page. I think I did a really good job with it and I also made the sections closer together so that there wasn't empty space on the page.

**Accessible CSS Code:**

	body {
   		**background: #ff9888;**
	}	

	.blurb h2 {
  		**color: #45161C;**
	}

	.blurb p {
   		**color: #510B23;**
	}

	#mainNavbar .nav-link {
    		**color: #45161C;**
	}

	#mainNavbar .nav-link:hover {
    		**color: #ffdfff;**
	}

	#mainNavbar .navbar-brand {
    		**color: #250005;**
	}

	#headingGroup span {
	    	**color: #ffdfff;**
	}

	.navbar.scrolled {
   		**background: #b48bb4;**
	}
