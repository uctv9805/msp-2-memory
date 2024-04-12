# Testing

## Manual Testing

- I regularly tested elements as I completed them, using the site preview within gitpod I could write the code and then test the site to make sure links worked and the website was responsive.

- I published the page on GitHub pages and then tested the website on different sized devices as well as different brand devices (android/apple/amazon/desktop) 
 to check responsiveness. 

- Let friends and family visit and use the website and report back any unusual findings or problems. 

- I used Chrome Developer tools to simulate different screen sizes in order to test responsiveness.

## Bugs & Fixes

1. Intended Outcome - Use original images on the card backs when they clicked the image would appear. 
    - Issue:
        - Could not get the array to recognise the images - kept showing as the text object and could not figure out how to make it work. 
    - Solution
        - Had to give up and simplfy the game, ended up using emojis so essentially it is just text showing up but at least it is visually more appealing than the words - intend to go back and rectify this in future. 

2. Intended Outcome - Site is responsive across all devices.
    - Issue:
        - Can not get the game board to scale properly on smaller devices such as mobile phone. 
    - Solution
        - Had to remove background images and keep it plain and simple for smaller devices.
    

# Post Development Testing

## Validator Testing

### HTML
No errors were returned when passing through the official W3C validator
- W3C Validator for [Find My Designs](assets/docs/screenshots/html-validator.png)

### CSS
I ran the validator and no errors were reported in my code

- Jigsaw Validator for CSS ![style.css validation](assets/docs/screenshots/w3c-css-validator.png)

## Lighthouse score

![index lighthouse score](assets/docs/screenshots/indexlighthousedt.png)


### Issue with performance and the solution
I was having trouble getting the performance above 90, especially on the gallery page but by reducing the image sizes this resulted in the scores being above 90 on multiple tests. To resize the images easily I used [imageresizer](https://imageresizer.com/).

## Accessibility

As well as the accessibility score from lighthouse testing I also used [WAVE - Web accessability evaluation tool](https://wave.webaim.org/extension/) to check my pages for accessibility and no errors were found.

[Back to README.md](README.md)