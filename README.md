# PC Flow 

![Image of site title and logo](source/artwork/logo.png?raw=true)

PC Flow is a website offering services building bespoke custom water-cooled PCs and conversions of pre-built machines.
 
## UX

This website is for PC enthusiasts who are interested in high performance systems for gaming and productivity work. People who want to get maximum performance out of their systems. This Website provides an opportunity for them to learn how water cooling can help not only improve computer performance, but also its aesthetic and acoustic properties.

### User Stories
* As a novice user, I want to learn more about water cooling, so that I can decide if it is right for me.
* As a potential customer, I want to know if PC Flow has the expertise to fulfil my needs.
* As a potential customer, I want to see examples of previous work, so I know what to expect.
* As a Customer, I want to be able to contact PC Flow quickly and easily, to get my order and needs addressed.

[Design document](/docs/design.pdf).

Design documents and source files can be found in the [docs](/docs/) folder.

### Sitemap
![site map](/docs/site-map.png?raw=true)

### Wireframes
#### Index (Home)
##### Mobile
![Mobile index.html](/docs/index.png?raw=true)

##### Desktop
![Desktop index.html](/docs/index-desktop.png?raw=true)

#### Showcase
##### Mobile
![Mobile showcase.html](/docs/showcase-alt.png?raw=true)

##### Desktop
![Mobile showcase.html](/docs/showcase-desktop-alt.png?raw=true)

#### Contact
##### Mobile
![Mobile contact.html](/docs/contact.png?raw=true)

##### Desktop
![Desktop contact.html](/docs/contact-desktop.png?raw=true)

#### Old Wireframes
**Old showcase.html layout**

![Mobile showcase.html](/docs/showcase.png?raw=true)

![Desktop showcase.html](/docs/showcase-desktop.png?raw=true)

## Features

### Existing Features

- Water cooling information section - allows novice users to learn about water cooling, so they can decide if it is right for them.
- The about me section - allows potential customers to learn about PC Flow's expertise to fulfil their needs.
- The showcase page - has examples of previous work so potential customers will know what to expect.
- The contact page - allows customers to contact PC Flow by filling out the contact form to get their needs addressed.
- A Prominent call to action on the home page helps direct users to content they need.

### Planned Features

- Make just the navbar sticky when scrolling so menu links are always available to users.
- Swapping relative units for pixel sizes for better responsiveness.

## Technologies Used

### Web Technologies
- [HTML5](https://html.spec.whatwg.org/multipage/)
	- PC flow uses **HTML5** for content and structure.
	
- [CSS3](https://www.w3.org/Style/CSS/specs.en.html)
	- PC flow uses **CSS3** for layout and styling.
	
- [JQuery](https://jquery.com/)
	- PC flow uses **JQuery** to simplify DOM manipulation, specifically for dynamic elements like 
	the navbar and showcase accordion.
	
- [Popper](https://popper.js.org/)
	- PC flow uses **popper js** to simplify positioning dynamic elements.
	
- [Boostrap](https://getbootstrap.com/)
	- PC flow uses **Bootstrap** to aid building responsive layouts and dynamic elements.
	
- [SVG](https://www.w3.org/Graphics/SVG/)
	- PC flow uses inline **SVG** for various theme-able vector graphics, such as icons and logos. 
	
- [Google fonts](https://fonts.google.com/)
	- **Google fonts** is used for to serve fonts for the title and body text.

### Developer Tools
- [Git](https://git-scm.com/)
	- PC flow uses **Git** for version control.
	
- [Github](https://github.com/)
	- PC flow development repository and hosting is through **Github**.
	
- [Gitpod](https://www.gitpod.io/)
	- PC flow was partially developed using **Gitpod**.
	
- [Textpad](https://www.textpad.com/)
	- PC flow used textpad for development and writing the README.md file.
	
- [Dreamweaver](https://www.adobe.com/uk/products/dreamweaver.html)
	- PC flow was partially developed using **dreamweaver**.

### Art creation
- [Photoshop](https://www.adobe.com/uk/products/photoshop.html)
	- **Photoshop** was used for editing photographs.
	- Photos taken with a Canon 5D DSLR camera.
	
- [Illustrator](https://www.adobe.com/uk/products/illustrator.html)
	- **Illustrator** was used for vector graphics creation such as icons and logos.

## Testing

### Device specific layout

#### Header and navigation
The header breaks down progressively for smaller screens to preserve space for content. On the smallest
screens it displays just a hamburger icon to show a drop down navigation menu and a small version of the
site logo.

On larger screens the logo is larger and hamburger icon and dropdown are replaced by a fixed navbar. On 
screens over 1200px wide content is prevented from growing beyond 1200px width to remain consistent with
site content sections.

#### Footer
The footer is a simple two column layout with a copyright notice on the left and social media icons on
the right. The copyright notice is shortened on small screens to "&copy; 2020" and expanding to
"Copyright &copy; 2020 Sean Young" on wider screens. The Social media icons also scale on small screens
so all content can remain on a single line.

#### Home page
The home page has a simple single column layout on all screens. On wider screens content is constrained
to 1200px width to aid readability.

#### Showcase page
On small screens the showcase page displays a single accordian stretching full width. If the screen is
higher than the content the content is centred vertically, otherwise it takes up the full page height.
The individual showcase sections are shown one at a time in a single full width column. On wider screens
the showcase sections have a full width three column layout. The Gallery grows from one image per-row, to
two and then four images per row. On screens greater than 1200px wide the showcase sections are constrained
to 1200px and horizontally centered.

The gallery callout scales progressively and is full width with small margins on smaller screens. On very
small screens the image caption is not displayed. On larger screens it is fixed size and horizontally centred.

#### Contact page
On small screens the contact form takes up full content height in a single horizontally centred column. On
larger screens the form has a two column layout centred horizontall and vertically with a maximum total width
of 850px to aid focus and readability.

### Testing process
Each element was tested for functionality during the development process. The following steps were also taken before 
final deployment on numerous browsers and devices:

- PC/Mac Browsers:
	- Chrome
	- Edge
	- Firefox
	- Opera
	- Safari
- Android
- iOS

### Link Testing
- Header, for each [page]:
	1. Load [page] (index.html, showcase.html, contact.html)
	2. Click PC flow logo image and verify it loads the home page (index.html). Return to [page].
	3. Click "Home" and verify it loads the home page (index.html). Return to [page].
	4. Click "Showcase" and verify it loads the showcase page (showcase.html). Return to [page].
	5. Click "Contact" and verify it loads the contact page (contact.html).
	
- Footer (Social media icons not yet implimented).

- Home page:
	1. Load home page
	2. Click "Contact Me" callout button and verify it loads the contact page (contact.html). Return to home page.
	3. Click "or read more" and verify it jumps to content section.
	4. Click showcase link and verify it loads the showcase page.
	
- Showcase page:
	1. Load showcase page
	2. Click each project tile and verify each content section is shown.
	3. Click gallery each image and verify the correct image appears in the modal.

- Showcase modal gallery:
	1. Open each showcase section
	2. Click on first image to bring up the callout and verify the correct image is displayed.
	3. Click next arrow until first image is re-displayed and verify each image is shown in the correct order.
			- Click each image and verify it opens the correct image in another tab.
	4. Click previous arrow until first image is re-displayed and verify each image is shown in the correct order.
	5. Click outside the modal window and verify it disappears. Re-open modal.
	6. Click X button in top right and verify modal window disappears. Re-open modal.
	7. Click close button in bottom right and verify modal window disappears.
	
### Layout testing
#### Browsers:
- Header, for each [page]:
	1. Load [page] (index.html, showcase.html, contact.html).
	2. Resize site width:
		1. Minimum break-point (220px), verify:
			- Background images and colors stretch to full width
			- Small logo used
			- Menu navbar is not displayed
			- Menu 'hamburger icon' is visible and toggles menu dropdown
			- No horizontal overflow
		2. Large phone break-point (450px), verify:
			- Background images and colors stretch to full width
			- Large logo used
			- Menu navbar is not displayed
			- Menu 'hamburger icon' is visible and toggles menu dropdown
			- No horizontal overflow
		3. Medium break-point (768px), verify:
			- Background images and colors stretch to full width
			- Menu 'hamburger icon' is not displayed
			- Menu navbar is visible
		4. Above maximum break-point (1200px), verify:
			- Header content doesn't grow beyond 1200px width
			- Background images and colors stretch to full width

- Footer, for each [page]:
	1. Load [page] (index.html, showcase.html, contact.html)
	2. Resize site width:
		1. Minimum break-point (220px), verify:
			- All footer text and icons remain in one line
			- Background images and colors stretch to full width
		2. Above maximum break-point (1200px), verify:
			- Footer content doesn't grow beyond 1200px width
			- Background images and colors stretch to full width

- Home page
	1. Load home page
	2. Resize site width:
		1. Minimum break-point (220px), verify:
			- Content doesn't overflow horizontally
			- Background images and colors stretch to full width
		2. Above maximum break-point (1200px), verify:
			- Content doesn't grow beyond 1200px width
			- Background images and colors stretch to full width

- Showcase page
	1. Load showcase page
	2. Resize site width:
		1. Minimum break-point (220px), verify:
			- Content doesn't overflow horizontally
			- Background images and colors stretch to full width
			- Showcase sections have correct single coloumn layout
			- Each showcase section is laid out in the correct order
			- Page scales vertically so all content can be seen or scrolled to
		2. Medium breakpoint (768px), verify:
			- Content doesn't overflow horizontally
			- Background images and colors stretch to full width
			- Showcase sections have correct two coloumn layout
			- Each showcase section is laid out in the correct order
			- Page scales vertically so all content can be seen or scrolled to
		3. Above maximum break-point (1200px), verify:
			- Content doesn't grow beyond 1200px width
			- Background images and colors stretch to full width
			- Page scales vertically so all content can be seen or scrolled to

- Contact page
	1. Load contact page
	2. Resize site width:
		1. Minimum break-point (220px), verify:
			- Content doesn't overflow horizontally
			- Background images and colors stretch to full width
			- Form has correct single column layout
			- Page scales vertically so all content can be seen or scrolled to
		2. Medium break-point (768px), verify:
			- Content doesn't overflow horizontally
			- Background images and colors stretch to full width
			- Form has correct two column layout
			- Page scales vertically so all content can be seen or scrolled to
		3. Maximum break-point (850px), verify:
			- Content doesn't grow beyond 1200px width
			- Background images and colors stretch to full width
			- Page scales vertically so all content can be seen or scrolled to
	
#### Devices
- Header, for each [page]:
	1. Load [page] (index.html, showcase.html, contact.html)
	2. Verify header is laid out according to design with no horizontal overflow.
	
- Footer, for each [page]:
	1. Load [page] (index.html, showcase.html, contact.html)
	2. Verify footer is laid out according to design with no horizontal overflow.

- Home page:
	1. Load home page
	2. Verify home page content is laid out according to design with no horizontal overflow.
	
- Showcase page:
	1. Load showcase page
	2. Verify showcase page content is laid out according to design with no horizontal overflow.
	3. For each showcase section verigy content laid out according to design with no horizontal overflow.
	
- Contact page:
	1. Load contact page
	2. Verify contact page content is laid out according to design with no horizontal overflow.

### Form Testing
- Contact page:
	1. Go to the Contact page
	2. Try to submit the empty form and verify that an error message about the required fields appears
	3. Try to submit the form with an invalid email address and verify that a relevant error message appears
	4. Try to submit the form with all inputs valid and verify that a success message appears.

NOTE: Form backend is not currently implemented

### Miscelaneous testing
[Markdown live preview](https://markdownlivepreview.com/) was used for checking the README.md file before 
committing.

### Known issues:
- At minimum break point (220px width) some header text overflows it's padding on index.html.

## Deployment

The site is deployed to github pages in a separate gh-pages branch.

The gh-pages branch was created in the github repository settings and deployed to using the command: 
>git subtree push --prefix site origin gh-pages

## Credits

###Content
- All text by Sean Young.
- Web-design by Sean Young.
- HTML and Styling by Sean Young.

### Media
- Logo/Title artwork by Sean Young.
- Logo/Title text based on 01Digitall font by David Chung (free licence) and Flow by Matt Chisholm (Free licence).
- Media icons and menu "hamburger" icon by Sean Young.
- Photographs by Sean Young.

### Acknowledgements
- Showcase Gallery code based on example code from [CSS Tricks](https://css-tricks.com/creating-a-modal-image-gallery-with-bootstrap-components/) by Diego Vogel
- Showcase Accordion based on example code from [Bootstrap](https://getbootstrap.com/docs/4.3/components/collapse/)
- Menu navbar based on example code from [Bootstrap](https://getbootstrap.com/docs/4.0/components/navbar/)