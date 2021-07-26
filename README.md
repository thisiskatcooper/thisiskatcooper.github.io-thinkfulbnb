# thisiskatcooper.github.io-thinkfulbnb
ThinkfulBNB FlexBox Project
<h1>Thinkfulbnb</h1>
Thinkfulbnb is a vacation rental website that allows people to rent out their homes to people who are seeking short-term accommodations in that locale. Thinkfulbnb hosts rent out different kinds of properties, including single rooms, apartments, and unique living spaces such as yachts, houseboats, yurts, tiny houses, and even renovated medieval castles.

For this assignment, you will implement Thinkfulbnb's landing page in HTML & CSS.

<h2>Thinkfulbnb views</h2>
The UX designer provided you with the following user interface mockups:

<h3>Mobile view</h3>
<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/Thinkfulbnb-mobile.png">

<h3>Desktop view</h3>
<img src="https://github.com/Thinkful-Ed/starter-thinkfulbnb/blob/main/images/Thinkfulbnb-desktop.png?raw=true">


<table>
<tr><th>File	Description</th>
  <th>Existing files</th></tr><tr><td>images/</td><td>A folder containing all the images used for the design.</td></tr><tr><td>index.html</td><td>The starter HTML file. You will need to add your solution to this file.</td></tr><tr><td>style.css</td><td>The starter css file. You will need to add your solution to this file.</td></tr></table>
You're encouraged to spend some time studying the provided files.

<h3>Setup</h3>
Use VSCode Live Server to launch the index.html page in your browser.

<h3>Tasks</h3>
For this assignment, you will be following a mobile-first development approach. To pass this assignment, you must complete the tasks detailed below.

You should use flexbox, and not floats, to achieve the desired layouts. The .group, .item, and .item-double classes are provided in the CSS file for your convenience, but it is not necessary to use them.

You are NOT expected to match the designs pixel by pixel, as long as the required layout is satisfied.

Edit the index.html and style.css as needed to achieve the following requirements:

<h3>Navigation</h3>
<ul>
  <li>The logo should stack on top of the menu links, which are aligned horizontally, as follows:</li></ul>
<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/navigation-mobile.png">

<ul><li>Single-page navigation: Modify the navigation links so that clicking on each link will take the user to the corresponding sections on the page, as follows:</li></ul>
<table>
  <tr><th>Link clicked</th><th>Take the user to the section with id of</th></tr>
  <tr><td>Stay</td><td>id="stay"</td></tr>
  <tr><td>About</td><td>id="about"</td></tr>
  <tr><td>Ideas</td><td>id="ideas"</td></tr>
  <tr><td>Host</td><td>id="host"</td>
  </table>
<h3>HTML form</h3>
<ul><li>In the "Find your perfect vacation rental" section, create a form that contains the following input fields with the specified types:</li>

  <li>Location: text input type, with a placeholder value of "Search destination"</li>
  <li>Arrive: date input type</li>
  <li>Depart: date input type</li>
  <li>Type: a dropdown list with the following options:</li>
Apartment, Barn, Castle, Houseboat, Tiny House, Yacht, Yurt
  <li>a "Search" button</li></ul>
  
<ul><li>Some CSS styles have already been written for you to help style your form. Add CSS to the form so that</li>

<li>the labels (i.e., "Location", "Arrive", "Depart", "Type") and their corresponding form fields are aligned towards the opposite ends of each row</li>
  
Your final form design should look as follows:

<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/search-form-mobile.png">

  <h3>Vertical content alignment</h3>
<ul><li>The content in the remainder of the sections (i.e., "About", "Ideas", "Want to become a Thinkfulbnb Host?"), including any text and images, should stack on top of each other. Refer to the mobile design shared above.</li></ul>

  <h3>Responsive images</h3>
<ul><li>Write CSS for all images so that the images will match whatever container width they are placed within, and changing the container sizes will update the image sizes appropriately.</li></ul>
  
  <h3>Media query: Desktop view</h3>
Now that your mobile design is looking good, you will need to adapt the design for the desktop view.

  <ul><li>In style.css, create a media query for screens that are wider than 480px.</ul></li>
Within the media query, write CSS to create the following designs for desktop:

<ul><li>The logo and the navigation menu links should be spaced apart from each other, like this:</li></ul>
<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/navigation-desktop.png">

<ul><li>The search form input fields and the button should be horizontally aligned, like this:</li></ul>
<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/search-form-desktop.png">

<ul><li>The items in the "About" section should be horizontally aligned. The paragraph content should be vertically centered and always be about twice as wide as each image item, like this:</li></ul>
<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/about-desktop.png">

<ul><li>The "Ideas" images should be displayed in a 2 by 2 grid (see the desktop design shared above).</li></ul>

<ul><li>The items in the "Want to Become a Thinkful Host?" section should be horizontally aligned. The paragraph content should be vertically centered and be as wide as each image item, like this:</li></ul>

<img src="https://raw.githubusercontent.com/Thinkful-Ed/starter-thinkfulbnb/main/images/host-desktop.png">

