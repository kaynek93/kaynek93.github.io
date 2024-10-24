# Box Bar Events website 
I have designed a website to help advertise a mobile trailer bar that can be hired out for weddings, parties, festivals. The website provides descriptive text on how the company started, the different packages they can provide and how someone is able to book the mobile bar for one of their events along with images so the user is able to see what the bar looks like. 

## Live Application:
https://kaynek93.github.io/

## Design Descisions 
#### Page Heading
An image of the box bar was used at the top of the page to instantly show the user what the website is for without them needing to read any words. I the used a large heading to show the company name and a subheading underneath for a desicription of what the website is about so the user isntantly knows what the website is for when they land on the page. 

#### Colours 
The design of the website has been kept as simple as possible and in keeping with the colours of the business, I used a light grey colour for the background (the same colour as the mobile bar). For all text blocks i have used a white background with a black font to make the text clear and easy to read. 

#### Font
The font family `serif` has been chosen, this is a very similar font to the font used on the signs that the business already uses so keeps the website on brand and simple to read.

#### Navigation 
There is a simple navigation under the title of every page, with the items in the navigation in the same order on every page to make it easy for the user to switch between pages. I used page anchors to make this possible and had every new page open within the same tab.

#### Image Gallery
There is an image gallery on the first page to help attract the users attention and to make them to want to find out more information on how to hire the mobile bar for thier events.

#### Screensizes
To help keep the website as scaleable as possible I have used % instead of px for most of my sizing to make sure that the website will still look good no matter what screen size the user is on. I have also used display flex to help with the positioning on the page.

#### Image links to external pages
On the contact page I used images of the logos for facebook and instagram to take the user to the social media pages for the company, I again did this by using anchors but i had these links open in a new tab. 

## WireFrames 
- [Home Page](metaData/wireFrames/Home.png)

- [About Page](metaData/wireFrames/About-us.png)

- [Contact Page](metaData/wireFrames/Contact-us.png)

- [Hire Page](metaData/wireFrames/Hire-us.png)

### External sources used for styling: 
[Flex direction (to align items stacked ontop of eachother)](https://www.w3schools.com/css/css3_flexbox_container.asp)

[Align items centrally](https://www.w3schools.com/cssref/css3_pr_align-items.php)

[Justify content (align items)](https://www.w3schools.com/cssref/css3_pr_justify-content.php)

[Sizing the images](https://www.w3schools.com/css/css_rwd_images.asp)

### Testing:
HTML - I have ran all my HTML pages through the `W3C
validator` and have fixed all errors. 

CSS - I have ran my CSS file through the `Jigsaw validator` and had no errors. 

I have also mamually tested the site, opening all links and using the navigation bar to move around the site.


# Developer Notes

## How to run the application locally:
To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

## Adding images to the image gallery 
To add more images to the image gallery.
1. First add your new image to the gallderImage folder, assests > images > galleryImages
2. Then in the index.html file add a new div inside the "image-gallery" div and change the src to point to the correct img. example below:

```
<div class="row">
        <img src="./assets/images/galleryImages/newImageName.png" alt="bar" class="gallery-image">
</div>
```

## Adding / Updating styles
All styling for the site can be found in the `main.css` file under assests > styles > main.css

Classes have been used across to the site so they can be reused to keep the styling consistant across the different pages. 

## Testing:
Before pushing up any new changes, ensure to check your changes pass the correct validators using the following: 

[HTML Validator](https://validator.w3.org/)

[CSS Validator](https://jigsaw.w3.org/css-validator/)

Manual Testing Procedures: To test the site manual please read the `Testing.md` documentation.
 
## Deployment Procedures:
Deployment of the live site is done using github Pages. When you commit and push a change to the repo it will automatically run the build and deploy checks. Once these checks have all passed your changes will be active on the live site. 

The build will go through 3 checks before deploying the changes: 
1. pages build and deployment / build (dynamic)
2. pages build and deployment / report-build-status (dynamic) 
3. pages build and deployment / deploy (dynamic) 

Live site url: https://kaynek93.github.io/ 