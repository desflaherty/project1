Project Name: DJ Black Coffee

I chose to build a website for a well known DJ called 'Black Coffee'. He is a South African DJ, record producer and singer-songwriter.He has released 5 albums to date and won the "Breakthrough DJ of the Year" award at the DJ Awards in Ibiza in 2015. He has a large following on social media but does not have a dedicated website. The creation of a website would promote his music and also increase his exposure on social media as well as providing a method to contact the artist or his management companies.

UX

Strategy: To create an online presence for the DJ as he currently does not have a dedicated website. There is a presence already on Facebook but this is to generic - a custom site would add value. 

The website would be designed for dance music fans or for dance music promoters who would be interested in finding out more about 'Black Coffee' or booking him for an event as well as his existing fan base.They would need to be able to view and buy his material and find out about tour dates and his activity on social media as well as a method to contact him. 
The site built enables visitors to listen to his latest album as well as providing a link to where they can purchase the album on amazon.co.uk. Visitors can also view a schedule of his upcoming tour dates and link to the respective website to purchase a ticket for these. The site provides links to his social media accounts on Facebook,Instagram and Twitter as well as YouTube videos. Visitors can also sign up to a mailing list and complete a booking request form. Management contact details are also provided.

User Stories:
As a dance music fan or promoter I would want to: 
listen to a latest album so that I can then purchase it if I like the music,
read about the DJ to become more interested in him as an artist,
view videos of his live performances so I can decide if I would like to go to his concert,
view his upcoming tour dates and link to a website where I can buy a ticket for a show,
view pictures of the artist to stay updated with his activity,
make a booking request through the website to book the DJ,
view contact information for his management if I work in the press industry or wish to have a direct contact method.

A Mockup for the website was created using the balsamiq software tool. Mockups for the proposed sections can be found in the project folder on github https://github.com/desflaherty/project1/tree/master/MockUp

Features:
Index.html - This is the home page for the website that provides links to the different sections in the website located on the navigation bar on the top right of the screen. A logo is used here as a home button. There is also an enquiry button that opens a modal form where a user can input their details for bookings or enquiries.
About.html - A biography section about the DJ and his awards etc.
Index.html#music - An embedded SoundCloud playlist where the user can listen to a sample of his Album in the browser window or link to SoundCloud as well as a link to Amazon.co.uk where the album can be purchased.
Index.html#video - Embedded videos from YouTube of live DJ sets.
Index.html#gallery - A series of photographs that link to the respective photo on his Instagram account.
Index.html#tour -Upcoming tour dates and location as well as links to the websites where tickets can be purchased.
Index.html#contact - Contact information for the DJs management company as well as a sign up form for his newsletter to receive the latest news.

Existing Features:
Index.html:
Black Coffee Logo  - which acts as a link to the home page when the user clicks on it.
Navigation Bar - allows users to clearly navigate to the different sections in the website. A underline text effect is implemented on mouse over as well as a fixed underline when the user is on a particular section. The underline effect works in conjuction with the scrollbar using bootstraps scrollspy feature. The underline effect is implemented using a separate css file called underline.css contained in the assets folder.
Nav bar toggle - drop down links for viewing the website on mobile.
A Enquiry button - allows users to completed a form entering their details for a booking or enquiry.
Index.html#music - Embedded SoundCloud playlist & link to amazon.co.uk site where the album 'pieces of me' can be purchased.
Index.html#video - Embedded videos fom YouTube that can be viewed in the browser window of the DJs live performances.
Index.html#gallery - Photos with external links to the respective photos that have been uploaded to by the DJ to his Instagram webpage.
Index.html#tour - Buttons that can be clicked on that will bring the user to the respective webpage where they can purchase tickets for the concerts.
Index.html#contact - A signup input form where the user can enter their e-mail details.
Footer/Social Media Links - Links to the DJ's Instagram, Twitter, YouTube and Facebook accounts.

Features Left to Implement:
Future plans could include more video and music content for future releases, a separate news section for articles and press releases, links to soundcloud and itunes beside the social media links. A more advanced collapsed menu for viewing the website on mobile.


Technologies Used:
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

HTML5
CSS
Bootstrap 3.3.7
Javascript
Font Awesome
Google Fonts
JQuery
Photoshop -  Trial version used to create the Logo used on the site from a photo sourced online. https://www.photoshop.com
DownloadGram - Third party software used to download photos from Instagram for use in the gallery section on the website https://downloadgram.com/



JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X
