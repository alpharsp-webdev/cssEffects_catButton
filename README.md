# cssEffects_catButton
Images with zoom in a light effect
Its a pretty nice effect if you have a website that divides in subcategories

## All you need for your project is the catButton.css file and the html structure below
  The images and the html file included here are only an example of how to use it

## All you need to do is: 
  ### On your html file:
  -Add a link to catButton.css file
  -Add the structure of the button where you want it (it will occupy the whole width of its container so if you need to make it smaller, just paste it inside another div and add a fixed width to containing div)
  -Add the image address (in the background-image part)
  -Add the name of your category (as text inside the span)
  
## html structure:
  ### Most things stay the same you only need to change the image address and the category name
      <!--Category starts-->
          <div class="catButton catRatio3-2">
            <div class="catButtonImage" style="background-image: url('yourimage.jpg');"> <!--Change id to your category name-->
              <div class="catTextContainer">
                <span class="catText">
                  <strong>CATEGORY NAME</strong>
                </span>
              </div>
            </div>
          </div>
      <!--Category ends-->
