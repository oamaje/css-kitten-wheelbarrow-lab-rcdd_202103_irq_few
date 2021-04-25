/* Select the image with a class of kitty-1 */

.kitty-1 {
  position: absolute;
  z-index: 1;
  top: 276px;
  left: 129px;
}

/* Select the image with id of kitty-2 */

#kitty-2 {
  position: absolute;
  z-index: 2;
  top: 212px;
  left: 369px;
}

/* Select the image inside the element with an id of basket (using its descendent relationship) */

#basket img {
  position: absolute;
  z-index: 5;
  top: 291px;
  left: 319px;
}

/* Select the image based on it being a sibling that follows immediately after the element with an id of ball (using adjacent sibling selector) */

#ball + img {
  position: absolute;
  z-index: 4;
  top: 260px;
  left: 455px;
}

/* Select the image that has an attribute value matching "Kitty 5" (using attribute selector) */

img[alt="Kitty 5"] {
  position: absolute;
  z-index: 3;
  top: 217px;
  left: 223px;
}

/* Congratulations! Now all your kittens are collected. */# CSS Kitten Wheelbarrow

## Problem Statement 
Oh no! All of our kittens have escaped from the wheelbarrow. Help collect all the kittens into the wheelbarrow using CSS selectors and absolute positioning. 

## Objectives
1. Practice absolute positioning skills

## Practice Absolute Positioning Skills

### Steps 
### Tasks for LearnIDE Environment Users 
1. Click the "OPEN IDE" button

### Tasks for Local Environment Users 
1. Fork this repository.
2. Clone your fork locally.
3. `cd` into the local repo you just cloned.

### Process

1. Open index.html in the browser. (For students using the Learn IDE, [use these instructions](http://help.learn.co/the-learn-ide/common-ide-questions/viewing-html-pages-in-the-learn-ide) on how to view HTML pages in the browser.)
2. Use the comments in **css/place-kitty.css** to write the correct selectors to move each kitty into the wheelbarrow.
