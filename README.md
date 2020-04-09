<h1>Berthe Morisot Art Tour Holidays</h1>
My project is the website for a fictious holiday company called Berthe Morisot Art Tour Holidays(the name chosen for no other reason than Berthe Morisot is one of my favourite female artists). The website contains information on the hotels, tourist attractions, museums, and cafes in any city that a user clicks on from a list of countries. The purpose of this website was to imagine that the company felt that their existing website was bland and unexciting, and did not stand out from the opposition. They wanted a website that would immediately convey to the viewer that they were specialists in their field, and with a layout and images to attract the artistically inclined tourist. It was also designed as my second milestone project to show the new skills learnt during the Javascript module, and interactive frontend modules.
<h2>UX</h2>
This website is for someone looking to plan different aspects of their holiday in their chosen city , with particular reference to hotels, museums, tourist attractions, art galleries .and cafes. The website is one page, broken up into sections. This was done purposely for it to be easier and quicker to navigate without the user having to wait for another page to load. It was designed to be well laid out and easy to read. <ul> <li> The Home page introduces the company, and sets the artistic tone of the company.</li> <li>The about page explains the variety and exclusivity of the holidays that Berthe Morisot holidays can offer, and gives a tempting list of destinations.</li> <li>The map page is designed to allow the user to select a country and city within that country of their choice from a list of options that the company operates in, and to make a judgement themselves as to where they want to spend their holiday by comparing options available in different destinations(options are hotels, cafes, museums, art galleries, and tourist attractions.) They can then make an informed decision as to which country and city is best for them. When they click on the markers that drop down, they are giving the ratings and website of the instituion, and all options are listed in a striped table, for ease  of reading. </li> <li>A contact form is designed to tempt the user to give their email address, and to begin a dialogue with the company with the business purpose of increasing sales of holidays, once the client has given their email address and signalled their interest. </li> <li>A fourth section shows a gallery of photos, again with the view of enticing the user with the prospect of holiday in one of these destinations A 'read more' button is used to explain the inspiration behind the company's name, and to create the sence that the clint will get a totally immersive and scholarly holiday given by exerts in the field from a company that are dedicated specialists in their line, of business.</li> <li>Afooter section contains social media sites for the user to learn and engage with company.</li></ul> 
<h3> To select a country.</h3>
The user clicks on the country autocomplete search bar, and clicks on an option from the dropdown list of countries.
<h3> To select a city</h3>
The user clicks on the enter a city search bar, and begins to type a name, or enough of a name , and then can click on one of the options from the dropdown menu that appears with suggestions of cities within the country choosen whoose names begin with the first letter typed.
<h3>To choose a category</h3>
To choose a category to search for the user clicks on one of the options from the dropdown list under the heading 'What are you looking for'. The reset button can be clicked to allow the user to search for another alternative. The options are hotels, cafes, museums, art galleries, and tourist attractions.
<h3> To use the map full screen feature</h3>
To open the map in full screen, click on the full screen button (a dashed square border in the top right hand corner of the map.)
<h3> To use the zoom feature</h3>
To use the map zoom feature, use the controls in the bottom right-hand corner of the map to zoom in and out.
<h3>To find the results of the user's selection</h3>
When a country, city, and option is selected, e.g. hotels, the autocomplete search will drop down markers on he map to show the location of the various hotels in that city. Each marker has an alphabetical letter to identify it in the  results table below. Double clicking on the marker on the map will give a dropdown listing the name, address, telephone number, and rating of the hotel. The same is true if art galleries, museums,cafes , or tourist attractions are choosen by the user. The name, address. telephone and rating of a hotel can also be displayed by clik=cking on an the alphabetical marker in the table of results and wiill appear over the marker on the map.
<h2>Features</h2>
<li>There is autocomplete in the searchbar allowing the user to begin typing and a list of cities in the selected country will appear. Usually, as soon as one letter is typed
 the autoselect will appear as a dropdown.</li>
<li>A category dropdown option allows the user to select and click on an option to search for from hotels, cafes, museums, art galleries, and tourist attractions.</li>
<li>By clicking on one of the markers, an information window appears showing the name, address, teleohone, and rating of the establishment</li>
<li>When clicking on the marker in the results table, the same information window appears on the map besides the selected marker.</li>
<li> A slideToggle feature when clicked on gives additional infomation about Berthe Morisot.</li>
<li>An email account was created and linked to my gmail account as 'Berthe Morisot' is a fictious company. Similarly, all social media sites were posted to apppropriate links as Berthe Morisot being a ficticious company did not have real ones.</li>
<h2>Technologies used</h2>
<li> HTML</li>
<li> css for styling in my style,css file.</li>
<li> Jquery was used to give the toggle button with additional information more dynamism.A speed for the slide of 1000 milliseconds was used.</li>
<li> Bootstrap4 was used for the navigation and button classes e,g, the reset button, and the slideToggle button.</li>
<li>Font-awesome was used for styling the social media icons</li>
<li> The Reset button was manually cheked multiole times to make sure all the markers from a previous search were removed. Clear results() function was also added to the reset buton so that the results table would clear also.</li> 
<li>Google fonts was used, and 'cookie' was chosen to give an artistic feel to match the project on art history based holidays. Similarly, the colour scheme, predominantly blue, pink and mauve was taken from the Berthe Morisot paintings used as backgrounds.<li>
<li>Javascript was used to make the website interactive, and to code the map and the autocomplete map search features and markers.</li>
<li>Google maps API, and Google maps Autocomplete Hotel Search documentation was used to allow the user to search for a country, city, and option.https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch?hl=. This was added to withtypes: [type.options[type.selectedIndex].value] to allow the user to select other options.<li>
<h2> Testing</h2>
<li>I manually tested the autocomplete in the search bar for 'Enter a city' by typing in many cities in a selected country, and each time the dropdown with the list of cities beginning with the letters typed appeared for each country tested. All countries on the select one option were tested.,/li.
<li>The options, hotels, cafes, museums, art galleries, and tourist attractions were tested for many cities in mant countries, and each time the map reset with different markers.</li>
<li> The markers were clicked on for enumerable choices to make sure that the relevant information window appeared with the name. address, telephone, and rating. Also, the markers in the result table were clicked on many times to make sure tha the information window appeared on the map by the same alphabetical marker. Clicking on the x was done to make sure that the marker disappeared.</li>
<li>The map features including the full screen choice(click on the dotted square border in the top right-hand corner.) To escape the full screen view, click on the icon in the top right-hand corner, the toggle between button, or press the escape key</li>
<li>The clicking of the zoom feature + or - was tested manually to ensure that the map zoomed in and out properly. </li>
<li> w3schools HTML validator was used to check for errors in my code, as well as w3css validator to check my style.css code.</li>
<li> I tested my project on several screen sizes, including<li>GalaxyS5</li><li>Google Chrome,</li><li> Microsoft Edge,</li><li> Firefox</li> 
<li>i phone x:tested using the inspect features on Chrome Developer tools</li>
<li>Browsers included:
Windows10:Google Chrome, Microsoft Edge, Firefox.</li>
<h2>Deployment</h2>
My site is deployed at <a href="https://margaretalice.github.io/Giverny/">click here to view</a>

<h2>Credits</h2>
en Hasselgren's milestone 2 project was a source of inspiration, and invaluable guideline for what a project using Google places hotel search should look like. But my main thanks and gratitude goes to wonderful mentor , Maranatha Ilesanmi, who takes my efforts and helps me make somehing worthwhile out of them.


   