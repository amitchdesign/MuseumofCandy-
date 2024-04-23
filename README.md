# MuseumofCandy-
The code and description of a mock front-end Museum of Candy information page.

This page was built in my website design certification course.

For this code, I worked on creating a responsive page with four rows set up with a picture on one side and text on the other. There is a responsive and sticky menu at the top of the page, and I used stock pictures that stayed true to the design. For this page, the inspiration is a bright pink Candy Shop paired with the fun of a museum. Since this page is not accessible, I had a lot of work ahead of me to make this bright page accessible but still fun! Below are all of the changes highlighted as ** **.

HTML CODE I chose not to use alt text for the images because they are purely decorative. The message of the webpage is conveyed without the description of the images.

Looking at the CSS Code the changes I made helped me make sure that this page is not only responsive but also accessible.

**Original CSS Code:**

.panel {
	**padding: 15px 25px;**
}

.pricing-plan {
	**border-bottom: 1px solid #e1f1ff;**
}

.pricing-img {
	**margin-bottom: 25px;**
	**max-width: 100%;**
}

.pricing-header {
 	**color: #888;**;
}

.pricing-features {
 	**margin: 50px 0 25px;**
}

.pricing-features-item {
  	**font-weight: 600;**
  	**font-size: 12px;**
 	**border-top: 1px solid #e1f1ff;**
}

.pricing-features-item:last-child{
   	**border-bottom: 1px solid #e1f1ff;**
}

.pricing-price {
    	**color: #016ff9;** 
}

.pricing-button {
   	**color: #348efe;**
}

.pricing-button:hover, .pricing-button:focus {
    	**background-color: #e1f1ff;**
}

.pricing-button.is-featured {
 	**background-color: #48aaff;**
  	color: white;
}

.pricing-button.is-featured:hover, .pricing-button.is-featured:focus{
 	**background-color: #269aff;**
  	color: white;
}


@media (min-width: 900px){
    .pricing-plan {
      	**border-right: 1px solid #e1f1ff;**
   }
}
By changing the colors, the font size and weight, the margins, and the padding, I was able to make the words more readable and easily seen no matter the size of your screen.


**Accessible CSS Code:**

.panel {
	**padding: 25px 25px;**
}

.pricing-plan {
	**border-bottom: 1px solid #53708a;**
}

.pricing-img {
	**margin-bottom: 12px;**
	**max-width: 110%;**
}

.pricing-header {
	**color: #5f5f5f;**
}

.pricing-features {
	**margin: 50px 0 50px;**
}

.pricing-features-item {
	**font-weight: 675;**
	**font-size: 14px;**
	**border-top: 1px solid #7797b3;**
}

.pricing-features-item:last-child{
	**border-bottom: 1px solid #7797b3;**
}

.pricing-price {
	**color: #0062da;** 
}

.pricing-button {
	**color: #2d7ad8;**
}

.pricing-button:hover, .pricing-button:focus {
	**background-color: #cce5fc;**
}

.pricing-button.is-featured {
	**background-color: #3d8cd1;**
}

.pricing-button.is-featured:hover, .pricing-button.is-featured:focus{
	**background-color: #0062da;**
}


@media (min-width: 900px){
	.pricing-plan {
		**border-right: 1px solid #7797b3;**
	}
}	
