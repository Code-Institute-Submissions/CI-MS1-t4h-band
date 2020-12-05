# METALLICA COVER BAND

## THE FOUR HORSEMEN

[View website in GitHub Pages](https://github.com/t4h-metallicacover-band/t4h)

This is the virtual HQ of the most important Metallica cover band from South America.
A responsive website for those interested in finding out more about the band's history and activities, our members, merchandising, upcoming shows and taking the band to their city/country.  

The website goals:
* Provide an easy way for the fans to find out more about tours and the upcoming shows
* Be the first website on Google's searches about Metallica cover bands.
* Be an important channel for those interested in hiring the band.
 
## UX

##### Visitors to this website are searching for:
* A contact channel for concert producers in hiring the band.
* Find out more about the band and the upcoming shows. 

##### This project is the best way to help them achieve these things because:
* Driven by search engines like Google, it has become the easiest way to contact the band's manager, the musicians and get a concert quote. 
* This website is very straightforward allowing the visitor with very few clicks find out everything that they are looking for about the band.

##### User stories
1. As a new fan of the band, I want find out more about the band and its musicians.
2. As a new/returning fan of the band, I want to easily navigate the site, so I can find what I need efficiently. 
3. As a new/returning fan of the band, I want to see the band pics and figure it out where and when the upcoming concerts will take place. 
4. As an interested concert producer, I want to get in touch with the band's manager, so I can ask for a quote.   
5. As an interested concert producer, I want to have access to band's material and reviews, so I can check the performance quality.
6. As a fan of the band/or interested concert produced, I want to follow the band on social media and keep up with its latest news.

##### Wireframe mockups: 

- [Home]()

## Features

Each page features a responsive **navigation bar** with conventional placing of **logo** (top left) and a highlighted "request a quote" button in the top right.
Each page has a **footer** with **copyright information** and **social media icons** linking to 5 the artists' social media pages. 

Every page - except the home page - features its own **hero image** at the top, detailing a drawing or painting by the artist, 
or in the case of the about page, a photo of the artist in her studio. 
The purpose of the hero image is to grab attention and give a positive emotional response to the user. 

##### Home

The Home page features a special hero image _or_ video. On mobile and tablet devices a full screen static image is seen. 
On desktops this is replaced with a promotional video, which autoplays on mute as a background element. Both of these elements have the page header displayed as an overlay.
The purpose of this hero image/video element is to give maximum impact on arriving at the website, while not using up people's data unnecessarily on mobile and tablet devices.

The home page **promotional video** hosted by Vimeo, engages the user and tells them the value of the products on offer.

After the special hero image/video is some **compelling copy** which reinforces the emotional response to the artist's work and the potential client's desire to add it to their lives.

Finally there is a simple **call to action button** guiding the user on their next step through the website - to *Visit the Gallery*.

##### About

The About page features **two photographs** of the artist in her studio, one professional headshot photograph, and a professional photograph of a painting in a fancy apartment.
The about page also includes some brief but compelling copy about the artist. 
*Enough information to satisfy curiosity without overwhelming the user*.

At the bottom of the page (above the footer) are two **call to action buttons**: *Visit Gallery* and *How to Order*. The How to Order button is highlighted. 

##### Gallery

The Gallery page is laid out in **columns of thumbnail images**, 2 columns wide for mobile devices, 3 columns wide for tablets and 6 columns wide for desktop. 
Each thumbnail is square and features a drawing or painting by the artist. 

Note: The design choice for 2 columns wide gallery preview on mobile is to encourage users to click the thumbnail and view the image in full. 
Viewing the images in full is much preferred by the artist to looking at images restricted by margins and padding. The thumbnails are still large enough to be easily clickable on mobile. 

Each can be clicked to open a **fancybox** window to view the artwork in detail, 
to move on to the next image, view the previous one, or return to the gallery page.

At the bottom of the gallery page the user is guided to choose from two **call to action buttons**: To view *Pricing* or learn *How to Order*. Again, the How to Order button is highlighted.

##### Contact

The Contact page features a **contact form**, which requests client name and email, provides a place to upload a photograph, and below that a box to leave a message. 
At the bottom of the form clients can **upload** photograph(s) they want the artist to use. 

The bottom of the form contains a **Send Button** 
 
### Existing Features

- Header Logo - Exists on [every page](../index.html) and allows all users to easily recognise the business brand. Clicking the logo returns users to the home page as they would expect.
- Header Navigation Bar - Exists on [every page](../index.html) and allows all users to easily navigate all the website's pages and find what they are looking for quickly.
- Footer Copyright Info - Exists on [every page](../index.html) and protects business copyright.
- Footer Social Icons - Exist on [every page](../index.html) and allows all users to access the social platforms that the artist uses.
- Call to Action Buttons - Exist on [every page](../index.html) and guide potential clients through the process of viewing artwork, learning about pricing and the order process, and finally making first contact for their order.
- [Promotional Video](../index.html) - Allows potential clients to connect with the artist, see her working in the studio and view some of her work. Creates connection and emotional response. 
- [About Page](about.html) - Allows potential clients to connect with the artist without overloading them with information.
- [Gallery Page](gallery.html) - Allows all visitors to the website to view thumbnail images of the artist's work. Each thumbnail can be clicked to open an individual fancybox viewer.
- [Fancybox Viewer](gallery.html) - Allows potential clients on the Gallery page to view the artist's work in more detail, to move to the next image, previous image or return to the gallery.
- [Pricing Tables](pricing) - Allow potential clients to understand the pricing of custom artwork by structuring it in an logical way. 
- [How to Order Steps Guide](how-to-order.html) - Allows potential clients to understand the steps involved in ordering their artwork.
- [Contact Form](contact.html) - Allows potential clients to ask questions, and/or make the first step in their ordering process. 
- [Upload option](contact.html) on Contact form - Allows clients to upload a photograph they would like the artist to use for their custom portrait.

### Features to Implement in future
- GDPR compliant pop-up screen - Allows all new visitors to the website to approve or deny the processing of their personal data. Ensures the business complies with the EU data protection law. - Javascript Needed
- Add CAPTCHA to contact form - Allows business to protect the contact form from spam. - Javascript Needed
- contact form Send button change from *Send* to *Processing* and then when complete changes to *Sent*. - Javascript Needed
- FAQ page, table with FAQs and dropdown buttons to view answers - Gives potential clients easy to find answers to their common questions. - Javascript Needed for dropdown functionality. Simple FAQ page could be implemented now.
- Artists' blog - Allows new potential clients to discover the website through articles written by the artist establishing her as a thought leader. - Artist currently doesn't have time to write a blog.
- Option to choose the language of the website - As the artist's second language is Dutch, this would allow Dutch speaking visitors to the website to view it in their native language. - Budget not available for professional translation at the time.


## Technologies Used

- This project uses HTML and CSS programming languages.
- [Cloud9](https://c9.io) - This developer used **Cloud9** for their IDE while building the website.
- [BootstrapCDN](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap4** to simplify the structure of the website and make the website responsive easily.
    - The project also uses BootstrapCDN to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [fancybox](https://fancyapps.com/fancybox/3/)
    - The project uses **Fancybox** for a gallery modal popup to view gallery images.
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
- [Vimeo](https://vimeo.com) 
    - The project used **Vimeo** to host the promotional video. 
- [jQuery](https://jquery.com/)
    - The project uses **jQuery** to reference Javascript needed for the responsive navbar, Vimeo video and Fancybox gallery modal.
- [Popper.js](https://popper.js.org/)
    - The project uses **Popper,js** reference Javascript needed for the responsive navbar.
- [AutoPrefixer](https://autoprefixer.github.io/)
    - This project used **AutoPrefixer** to make sure the css code is valid for all browsers.
- All external images are stored and linked from a **Wordpress Media library** owned by the artist.


## Testing 

Testing information can be found in separate [TESTING.md file](TESTING.md)

## Deployment

This project was developed using the [Cloud9 IDE](https://c9.io), committed to git and pushed to GitHub using the built in function within cloud9. 

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/AJGreaves/portrait-artist), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **AJGreaves/portrait-artist**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.

At the moment of submitting this Milestone project the Development Branch and Master Branch are identical. 

### How to run this project locally

To clone this project into Gitpod you will need:
1. A Github account. [Create a Github account here](https://github.com/)
2. Use the Chrome browser 

Then follow these steps:
1. Install the [Gitpod Browser Extentions for Chrome](https://www.gitpod.io/docs/browser-extension/)
2. After installation, restart the browser
3. Log into [Gitpod](https://gitpod.com) with your gitpod account.
4. Navigate to the [Project GitHub repository](https://github.com/AJGreaves/portrait-artist)
5. Click the green "Gitpod" button in the top right corner of the respository
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally.

To work on the project code within a local IDE such as VSCode, Pycharm etc:
1. Follow this link to the [Project GitHub repository](https://github.com/AJGreaves/portrait-artist).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open the terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

## Credits

### Content
- The text for the Home page and About page was created for Anna Gilhespy by [Catriona Black](https://nl.linkedin.com/in/catrionablack).
- The text for the rest of the website was created by Anna Gilhespy and proof-read/edited by [Catriona Black](https://nl.linkedin.com/in/catrionablack).

### Media
- All the photos used in this site were obtained from the artist - Anna Gilhespy.
- Professional photography on images about1.jpg and about3.jpg on the About page by [Rudi Wells Photography](https://headshots.amsterdam) and obtained from the artist - Anna Gilhespy.
- The video on this website was produced by [Luke Davis](https://about.me/lukedavies) and obtained from the artist - Anna Gilhespy.

### Code
- CSS code for shadows and hover responsiveness of gallery images was originally taken from [Material Design Box Shadows| A Pen By Samuel Thornton](https://codepen.io/sdthornton/pen/wBZdXq) and then edited.
- CSS code for overlays on index.html page originally taken from [FullScreen YouTube Video Background In Pure CSS](https://codepen.io/dudleystorey/pen/PZyMrd])

### Acknowledgements

- I received inspiration for this project from my own experience of building and maintaining a WordPress website for this business in the past years. 
- My mentor Simen Daehlin guided me towards attempting the special responsive header on the Home page.

#### Disclaimer

The content of this Website is for educational purposes only.


### A note to my fellow Code Institute students

I am happy that you have come to look at my readme as an example of how to write a good one for your first Milestone project. 
You are welcome to learn how to structure and format your own readme from mine. 

However, it is not ok to copy and paste large portions of it into your own project. 
Please remember to write your own readme yourself, rather than copying mine or someone elses. 

Many thanks! Anna 