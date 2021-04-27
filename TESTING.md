# Aled Garfield Photography - Testing 

I have tested my site to ensure that it achieves the intended aims of the owner and the expectations of the users by meeting the user stories detailed in the [README.md](https://github.com/AledPeart/MS1-Aled-Garfield-Photography/blob/master/README.md). I have also manually tested my site across a number of different devices and browsers to ensure that the design, layout and functionality respond as intended. In addition the validity of my HTML and CSS have been checked using the [W3C Markup](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/). Finally I have used ]Lighthouse](https://developers.google.com/web/tools/lighthouse) in Chrome DevTools to test the accessibility and performance of my site. The specific tests and results are detailed below:

## User Stories

 **As a potential customer visiting the website I want a pleasant user experience and be able to navigate around the site easily**. 
-	Clear Navigation bar with easily accessible links
-	Brand logo always links back to the homepage
-	Link buttons in the subsections guide the user through the site
-	Footer link allows the users to return to the top of each page without needing to scroll.
-	Layout is uncluttered and visually pleasing
-	Images used with text content to provide a visual component

**As a potential customer visiting the website I want to see the information presented in a clear concise and logical way**. 
-	Clear Navigation bar with easily accessible links
-	Content is kept concise and separated into visually distinct blocks containing key information
-	Layout is uncluttered and visually pleasing

**As a potential customer visiting the website I want to hear about other people’s experiences of working with the photographer**. 

-	Testimonial section on the Home page highlights past customer’s positive experiences


**As a potential customer visiting the website I want to see examples of the photographers best work so that I can decide if I would like to hire them to photograph my wedding**. 

-	Portfolio page containing a gallery of the photographers work
-	‘Hero’ image on the homepage, and selected image in the ‘view my portfolio section’
-	Links provided to social media accounts where more work can be viewed

**As a potential customer visiting the website I want to learn more about the style of photography offered**. 

-	About-Me page contains a detailed description of the photographer’s style and approach


**As a potential customer visiting the website I want to learn more about the photographer**. 

-	About-Me page contains a information about the photographer.


**As a potential customer visiting the website I want to be able to easily view the photographers social media channels**. 

-	Social media channels are linked via recognisable visual icons in the footer


**As a potential customer visiting the website I want to be able to easily contact the photographer**. 
-	Contact page contains a form enabling users to contact the photographer directly
-	Contact page is linked to from each page




## Manual Testing

### Internal Links

#### Do all internal links in the Navigation Bar perform as expected and link to the correct page and open within the existing browser window?

* __Test__- When clicked from each of the 3 pages (portfolio, about me, contact) the ALED GARFIELD brand logo in the navigation bar should link back to the homepage within the existing browser window.  
__Result__– The result was as expected.

* __Test__– When clicked from each of the 4 site pages the navigation links in the navigation bar should link to the correct page and open within the existing browser window.  
__Result__– The result was as expected.

#### Do all internal button links perform as expected and link to the correct page and open within the existing browser window?

* __Test__– When clicked the View My Portfolio button on the Home page should link to the Portfolio page and open within the existing browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Learn More button on the Home page should link to the About Me page and open within the existing browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Contact Me button on the Home page should link to the Contact page and open within the existing browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Contact Me button on the Portfolio page should link to the Contact page and open within the existing browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Contact Me button on the About Me should link to the Contact page and open within the existing browser window.  
__Result__– The result was as expected.

#### Does the internal link in the Footer section perform as expected and link to the correct page area and open within the existing browser window?

* __Test__– When clicked from each of the 4 site pages the Back To Top link in the Footer section should return the user to the top of the current page and not open a new browser window.  
__Result__– The result was as expected.

### External Links

#### Do all external links on the site perform as expected and link to the correct place and open in a new browser window?

* __Test__– When clicked the Whimsical Wonderland badge in the Footer section should link to the Whimsical Wonderland page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Love My Dress badge in the Footer section should link to the Love My Dress page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Rock My Wedding badge in the Footer section should link to the Rock My Wedding page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Cwtch the Bride badge in the Footer section should link to the Cwtch the Bride Facebook page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Facebook Icon in the Footer section should link to the Aled Garfield Facebook page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Twitter Icon in the Footer section should link to the Aled Garfield Twitter page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Instagram Icon in the Footer section should link to the Aled Garfield Instagram page and should open a new browser window.  
__Result__– The result was as expected.

* __Test__– When clicked the Pinterest Icon in the Footer section should link to the Aled Garfield Pinterest page and should open a new browser window.  
__Result__– The result was as expected.

## Responsiveness 

I have tested my site across 5 screen widths in order to best replicate the breadth of modern viewing devices, in order to ensure that the site responds and performs as expected. These are also the Bootstrap ‘breakpoints’ adhered to when building the website:

* Extra Small 	<576px  
* Small		576-768px  
* Medium		768-992px  
* Large		992-1200px  
* Extra Large	>1200px  

These tests were carried out using Chrome DevTools to adjust the screen size and view the website at the designated screen widths.

### Extra Small

#### Page Header

* __Test__– The navigation bar should appear as expected; the brand logo is on the left, and the navigation links are collapsed inside a ‘burger’ icon on the right. The spacing of the items is consistent with the intended design.  
__Result__– The result was as expected.

* __Test__– When clicked the ‘burger’ icon menu should expand under the brand logo.  
__Result__– The result was as expected.

#### Page Footer

* __Test__– The page footer appears as expected, with the featured badges stacked in two columns and the social media icons in four columns. The ‘back to top’ link is stacked above the copyright text.  
__Result__– The result was as expected.

#### Home Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– The kind words section shows two testimonials; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.


#### Portfolio Page

* __Test__– The gallery images appears as expected; the images stack appropriately on top of each other with consistent padding between each image.  
__Result__– The result was as expected.


* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### About Me Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Contact Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

* __Test__– The Contact Form Takes up 100% of the screen width.  
__Result__– The result was as expected.

### Small

#### Page Header

* __Test__– The navigation bar should appear as expected; the brand logo is on the left, and the navigation links are collapsed inside a ‘burger’ icon on the right. The spacing of the items is consistent with the intended design.  
__Result__– The result was as expected.

* __Test__– When clicked the ‘burger’ icon menu should expand under the brand logo.  
__Result__– The result was as expected.

#### Page Footer

* __Test__– The page footer appears as expected, with the featured badges and social media Icons in four columns and the ‘back to top’ link stacked above the copyright text.  
__Result__– The result was as expected.

#### Home Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– The kind words section shows two testimonials; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.


#### Portfolio Page

* __Test__– The gallery images appear as expected; the images stack appropriately on top of each other with consistent padding between each image.  
__Result__– The result was as expected.


* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### About Me Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Contact Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

* __Test__– The Contact Form Takes up 100% of the screen width.  
__Result__– The result was as expected.

### Medium

#### Page Header

* __Test__– The navigation bar should appear as expected; the brand logo is on the left, and the navigation links are laid out on the right. The spacing of the items is consistent with the intended design.  
__Result__– The result was as expected.

#### Page Footer

* __Test__– The page footer appears as expected, with the featured badges and social media Icons in four columns. The copyright text appears on the bottom left and the ‘back to top’ link is on the right.  
__Result__– The result was as expected.


#### Home Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– The kind words section shows two testimonials; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Portfolio Page

* __Test__– The gallery images appear as expected; the images appear in a 3-column mosaic gallery with consistent padding between each image.  
__Result__– The result was as expected.

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### About Me Page

* __Test__– The layout appears as expected; the columns in each section are side-by side with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Contact Page

* __Test__– The layout appears as expected; the columns stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

* __Test__– The Contact Form Takes up 75% of the screen width.  
__Result__– The result was as expected.

### Large

#### Page Header

* __Test__– The navigation bar should appear as expected; the brand logo is on the left, and the navigation links are laid out on the right. The spacing of the items is consistent with the intended design.  
__Result__– The result was as expected.



#### Page Footer

* __Test__– The page footer appears as expected, with the featured badges and social media Icons in four columns. The copyright text appears on the bottom left and the ‘back to top’ link is on the right.  
__Result__– The result was as expected.

#### Home Page

* __Test__– The layout appears as expected; the columns in each section align side-by-side with adequate spacing.  
__Result__– The result was as expected.

* __Test__– The three portfolio images as expected; aligning side-by-side with equal spacing.  
__Result__– The result was as expected.

* __Test__– The kind words section shows three testimonials; the columns align horizontally across the screen with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Portfolio Page

* __Test__– The gallery images appear as expected; the images appear in a 3-column mosaic gallery with consistent padding between each image.  
__Result__– The result was as expected.

* __Test__– The layout appears as expected; the sections stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### About Me Page

* __Test__– The layout appears as expected; the columns in each section are side-by side with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Contact Page

* __Test__– The layout appears as expected; the sections stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

* __Test__– The Contact Form Takes up 50% of the screen width.  
__Result__– The result was as expected.


### Extra Large

#### Page Header

* __Test__– The navigation bar should appear as expected; the brand logo is on the left, and the navigation links are laid out on the right. The spacing of the items is consistent with the intended design.  
__Result__– The result was as expected.

#### Page Footer

* __Test__– The page footer appears as expected, with the featured badges and social media Icons in four columns. The copyright text appears on the bottom left and the ‘back to top’ link is on the right.  
__Result__– The result was as expected.

#### Home Page

* __Test__– The layout appears as expected; the columns in each section align side-by-side with adequate spacing.  
__Result__– The result was as expected.

* __Test__– The three portfolio images as expected; aligning side-by-side with equal spacing.  
__Result__– The result was as expected.

* __Test__– The kind words section shows three testimonials; the columns align horizontally across the screen with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Portfolio Page

* __Test__– The gallery images appear as expected; the images appear in a 3-column mosaic gallery with consistent padding between each image.  
__Result__– The result was as expected.

* __Test__– The layout appears as expected; the sections stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### About Me Page

* __Test__– The layout appears as expected; the columns in each section are side-by side with adequate spacing.  
__Result__– The result was as expected.

* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

#### Contact Page

* __Test__– The layout appears as expected; the sections stack appropriately on top of each other with adequate spacing.  
__Result__– The result was as expected.


* __Test__– All images render correctly and maintain their original ratio with no distortion  
__Result__– The result was as expected.

* __Test__– The Contact Form Takes up 50% of the screen width.  
__Result__– The result was as expected.


## Cross-Browser Testing

To further ensure my site was functioning as expected I have tested it across different browsers at different device sizes. The other browsers I have tested are Safari and Firefox, which combined with Chrome, account for almost 90% of browser usage (source: (www.browserstack.com) I tested the site on these browsers, on physical devices, which I have access to, namely:

*	A large screen desktop
*	Laptop
*	Tablet
*	Mobile device

I followed the testing criterias that I have detailed above for my Manual Testing, but I have not detailed the results of the tests in full detail here as I feel it would prove too lengthy for it’s intended purpose. I have however summarised the results and the issues encountered below:

### Large Screen Desktop

__Firefox__ – Hover function not working correctly on the ‘as featured’ badges   
__Safari__ – external links open in a new window rather than in a new tab.

### Laptop

__Firefox__ – no issues found 
__Safari__ – no fade on badges__

### Tablet 

__Firefox__ – Hompepage images distorted when tablet held in landscape mode  
__Safari__ - Hompepage images distorted when tablet held in landscape mode

### Mobile 

__Firefox__ – no issues found  
__Safari__ – Unable to test, no access to an IOS mobile device, and current covid-19 restrictions prevented me from sourcing one.


## HTML and CSS Validation

While developing I have regularly validated ny HTML and CSS using [W3C Markup](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/).  
Errors and Warnings that were highlited to me that I addressed during the project were:
* Image filenames containing capitals
* Missing closing </div> tags
* __section__ tags that did not have an __h1__ or an __h2__ as a direct child
* Missing __:__ and __}__ in my css file

At the time of submission the results are showing no errors (see screenshots below)

[index.html](MS1-Aled-Garfield-Photography/assets/images/w3-validation-check-index.png)  
[portfolio.html](../assets/images/w3-validation-check-portfolio.png)  
[about.html](../assets/images/w3-validation-check-about.png)  
[contact.html](../assets/images/w3-validation-check-contact.png)  
[style.css](../assets/images/w3-validation-check-css.png)

