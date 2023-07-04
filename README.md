![Haven Hub Logo](/assets/images/havenhub-logo.png)

Welcome,

**Haven Hub Care Services Limited** is an organisation that specialises in providing assisted living for people with special needs and is based in the United Kingdom. The website seeks to present key contact information about the organisation, and collect information from people that are interested in its services and offers. The link to the deployed site is <a href="https://dcsndevs.github.io/haven-hub/">Here</a>

## **Features**
<hr>

`Navigation Bar:`
The Navigation bar is replit acrros the pages of the entire website. It helps the users of this website to easily move from one page to the other. It also bares a phone number which can be dialed via a single click, if the user is browsing through a mobile device. The navigation bar also includes a Location link that can automatically list the address to the organisation on google maps, rather than typing the address manually. Finally the Navigation bar includes the organisation logo wirtten in large fonts, in other to help the user know with ease, that they are on the Haven Hub website and to also give a feel of the organisation's brand.

`Hero image with text:`
The main image shows a staff administering medication to a client in a residential setting. A bold introductory message immediately lets the user know that this is a organisation that specialises in supported living and housing accommodations.

``About Us & Services Section:``
This section is immeidately under the hero image, and it is also a page. It can be viewed by either scrolling down further or by clicking the "About us" link on the navigation bar.
This section welcomes the user to the website with a brief introductory message of what the organisation does.
This section is divided into four sections and each of the remaining three sections explains the kind of services that is provided by the organisation.

`Get Involved:`
Below the About Us & Services section is the Get Involved section. This section can be visited by further scrolling or by clicking the Get Involved link on the menu on the navigation bar. It consists of thre responsive cards that visually depicts a call to action for the user. It immediately lets the user know that they can be invovled in three ways - Volunteer, Donation, and Leasing their property to the organisation.

`Subscribe to Newsletter:`
This section is found towards the bottm of the page and it helps the user signup up to the organisation's newsletter. It was built with ease and seeks to secure the subscription by just accepting one input field and then collecting the user's email address.

`Footer:`
Like the Navigation bar, the footer maintains the same design and content through out all the pages of the website. It contains the organisation's social links which when clicked opens the social site on a new window and still keeps Haven hub's website open. This helps the user to still stay active in what they were doing on the organisation's website. 
The footer also contains the organisation's phone number and physical address/ The address when clicked also opens a google map for ease of direction.Likewise, the phone number when clicked, would attempt to dial the number if the user were using a mobile device  ora computer that has Call abilities.

`Sign Up Page:`
The Signup page (https://dcsndevs.github.io/haven-hub/contact-us.html) contains a web form that collects the users data based on the reason why they are contacting the organisation. The user has the options and choose to become a client, Donate, Volunteer, Lease their property and subscribe to the organisation's newsletter.
At the moment, the form is not connected to any database but only make use of a 'Get' form action. There are future plans of connnecting it using Javascript, PHP and MYSQL in order to store what is submitted.

`Thank you Page:`
There are two thank you page with same layout but different messages. 
The first, (https://dcsndevs.github.io/haven-hub/contact-us.html) is a message that users who Signed up via the contact us page gets to see. It informs the user that their deatils have been received, and that they would be contacted shortly.
The second, (https://dcsndevs.github.io/haven-hub/newsletter-thankyou.html) refers to users who specificaly used the Newsletter subscription form from the hompage. It lets the user know that they have successfully scubscribed to recevie newsletter from the organisation.

There is a future plan to allow the user receive a pop-up after submitting through the contact page and then gives the user an option to return to the homepage. This would reduce the number of pages for the website as a whole, and is a faster and more user friendly method rather than allowing another page load before confirming actions to the users.

## **Testing**
<hr>

Various tools have been used in testing the the overall performance of the website from begining to end. I have listed them in no particular other below:

`Google PageSpeed Insights:`
Google page speed insights was used to test the speed of the website and various issues were highlighted which was followed by subsequent adjustments.
A notable issue raised was that of the body font bing high in contrast. The font (Diphlliea) was then changed to Roboto. High contrast fonts are difficult to read by some users and also on some devices.

`HTML Validator:`
1. The W3 validator (validator.w3.org) highlighted errors on the website's links. Arial-label instead of aria-label had been used, and 15 errors were found and corrected.
2. An element hhad been left exposed on the about section and this was detected and corrected afterwards. Click the image below to visit the validation page!
<p>
    <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fdcsndevs.github.io%2Fhaven-hub%2F">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss-blue"
            alt="Valid CSS!" />
    </a>
</p>

`CSS Validator:`
1. The W3 validator highlighted 5 errors regarding the use of a wrongly written code for background-color, align-items and position. These codes were then rewritten correctly.
2. The validator highlighted 5 warnings regarding using same background color and border colors for the buttons on the pages.
Click the image below to visit the validation page!
<p>
    <a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdcsndevs.github.io%2Fhaven-hub%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

`Color Contrast:`
Deque's University Color Contrast Analyzer was used to determine what colors go together This ensures that users of all kind can clearly view texts and image/button borders. Some users might be color blind or are people with low vision experience. This tool ensures that the best colours are used in other to gurantee their convenience. A brief understanding of this would be an instance where a white text is put on a yellow backrougnd. Both colors are too bnright and would be difficult to read for most users.
https://dequeuniversity.com/rules/axe/4.7/color-contrast

            
`Unfixed Bugs:`
At the time of documenting, there are no know bugs yet.

## **Deployment**
<hr>
The site was deployed using Github and was pushed through via Vscode.
The repository was created on Github and then cloned on Vscode. After creating the site on Vscode, it was pushed onto github.
The site was then deployed via Github pages by -
<li>Selecting the settings tab inside the repo on Github </li>
<li>Selecting Deploy from a branch under 'Build and deployment'</li>
<li>Selecting Main under branch</li>
<li>Click save</li>
After these steps, the site would have been deployed and becomes live at https://dcsndevs.github.io/haven-hub/

## **Credits**
<hr>

`Content`
<li>The text of the whole website was written with the help of Open Artificial intelligence <a href="https://chat.openai.com/">Chat GPT</a>.</li>
<li>While creating the elements on the index page, I struggled with aligning the texts and contents to an absolute center. I was then introduced to the Flex box tutorial by <a href="https://www.youtube.com/user/KepowOb">Kelvin Powell</a> on <a href="https://www.youtube.com/watch?v=hwbqquXww-U&list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd&ab_channel=KevinPowell">YouTube</a></li>
<li>In preparation for this website, I used Balsamiq to create wireframes to guide me through the project. Even though the final website didn't look exactly like the wireframe, it provide a guide on the journey and was important to helping me achieve the final design.</li>

``Fonts & Icons``

The fonts used were imported from <a href="https://fonts.google.com/">Google Fonts</a> and the Icons were from <a href="https://fontawesome.com/">Font Awesome</a>.

`Colors`

Black, Dark Green, Ivory, and Yellow were the main colors used for this site. <a href="https://www.hostinger.com/tutorials/website-color-schemes">Hostinger's</a> color scheme tutorial inspired the use of Dark Green, Ivory, and Yellow. The color pallete according to it, suggests they are "easy on the eyes, making the website seem relaxing and organic"

``Animations``

The animation used for the intro message is "text-focus-in" animation gotten from <a href="https://animista.net/play/text/focus-in/text-focus-in">Animista</a>

`Images`

<ul>
<li>All the images used in the creation of this website were sourced on Pexels, Unsplash and W3 websites. Below is a list of the images used and there links: 
<ol>
<li>Photo by <a href="https://www.pexels.com/photo/woman-in-white-shirt-sitting-beside-woman-in-black-long-sleeve-shirt-7551652/">Kampus Production</a></li>
<li>Photo from <a href="https://www.w3schools.com/w3images/house2.jpg"> W3 Web Themes</a></li>
<li>Photo by <a href="https://unsplash.com/photos/8irA6aCfgDs">Doan Anh</a></li>
<li>Photo by <a href="https://www.pexels.com/photo/joyful-adult-daughter-greeting-happy-surprised-senior-mother-in-garden-3768131/">Andrea Piacquadio</a></li>
<li>Photo by <a href="https://www.pexels.com/photo/2-person-holding-hands-45842/">Pixabay</a></li>
</ol>
</li>

<li>
<a href="https://imageresizer.com/">Image Resizer</a> and <a href="https://tinypng.com/">Tiny Png</a> were used to respectively esize and compress all the images on this site.
</li>
<li>
<a href="ami.responsivedesign.is">Am I Responsive</a> website was used to simultaneously display how the site looks on different screen sizes.
</li>
</ol></ul>



`Acknowledgements`

In the build up of the website, I got a lot of inspiration from my Mentor <a href="https://github.com/IuliiaKonovalova/">Julia Konn</a> who guided me through out this work. She explained difficult terminologies and helped break down complex structures.

I wish to thank my loving wife for her support in the course of this work. She's been taking up most of my shifts for baby sitting our son in other to allow me give more time to this work.
