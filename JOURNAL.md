## Abstract ##
This portfolio encapsulates the development journey of crafting a small, accessible website rich with multimedia content, adhering to valid HTML & CSS standards. It comprises two pivotal stages:

**Task 1: Initial Designs**

In this phase, meticulous design documentation was prepared, showcasing the envisioned appearance and functionalities of the website across mobile and desktop interfaces. Emphasis is placed on accessibility, ensuring compatibility across diverse hardware/software platforms, and accommodating users with disabilities. Features such as screen-reader support, intuitive navigation, and inclusive design elements are delineated. The design documentation serves as a blueprint for subsequent development iterations.

**Task 2: Website and Journal**
The culmination of this endeavour involves the realisation of the designed website and the maintenance of a comprehensive development journal. When deployed, the website will reflect iterative enhancements and thorough testing conducted throughout the development process. The journal elucidates the evolution of the project, documenting sprint objectives, achieved milestones, testing outcomes, and rationale behind design modifications. It encapsulates a journey of learning and adaptation, culminating in the creation of an accessible digital platform.
Throughout this portfolio, adherence to Agile principles, particularly a modified Scrum methodology, underscores the iterative nature of development, fostering flexibility in accommodating changing requirements. Validations and testing are integral components, ensuring adherence to HTML and CSS standards, as well as verifying the functionality and appearance of the website. Utilisation of third-party code is judiciously acknowledged, enriching the website's functionality while maintaining code integrity.

## Iterative Development ##

I will be using my GitHub account https://github.com/tobybeevers/5HTMLWebsite to document the journey of my HTML & CSS project, I aim is invite my peers and encourage a Peer Code review process throughout the project.
Sprints will be managed as below;

| Sprint Name | Date   | Release Aims                                       |
|-------------|--------|----------------------------------------------------|
|Jan24        | 1-31st |Foundations, Designs, Accessibility, Documentation  |
|Feb24        | 1-29th |CSS Style Sheets, basic HTML and page set up        |
|March24      | 1-31st |Rich media, external content, and images            |
|April24      | 1-30th |HTML Content, Accessibility and Responsiveness      |
|May24        | 1-31st |Final testing, validation of code, final journal    |


## Iteration One ##
|Date	                |Aims & Objectives	         |Release       |
|---------------------|----------------------------|--------------|
|01/01/24 to 31/01/24	|Create project plan and initial document for approval.|25/01/24 |
|                     |Review the subject of Accessibility in Web Development.| |
|                     |Review the subject of HCI in Web Development.	   | |

**Sprint Notes & Development Decisions**

This sprint is about research and setting the foundations for the website, a list of tasks from my GitHub project https://github.com/users/tobybeevers/projects/2.
 
*Project Plan*

Created the Project Plan for Broughton Life this also contains the basic Wire Frames and Advanced Wire Frames which have been created on Balsamiq.com.

*Accessibility*
As mentioned above in the Reading & Considerations section above this has been a real learning curve and become a key consideration. (W3C Org, 2023)

**Sprint Retro**
|What’s Gone Well      |What Could Have Been Better |
|----------------------|----------------------------|
|Project Planning, documentation etc	|More time understanding Accessibility and HCI |


## Iteration Two ##
|Date	                |Aims & Objectives	         |Release       |
|---------------------|----------------------------|--------------|
|01/02/24 to 29/02/24	|CCS Style Sheets|29/02/24 |
|                     | Basic 5 Page Set Up   | |
|                     |Navigation Bar| |

**Sprint Notes & Development Decisions**

Second sprint is about setting out the basics of the webpage, the aim is to create the CSS Style Sheets and apply the styles from the design documentation 6. Colours, Fonts & Branding. Also so to set up the HTML Pages and Head etc.
 
*CCS Style Sheets*

I began the CCS with the styles taken from the design sheet, it become apparent early that Font Weight and Sizes would need to be changed.
I also took advantage of the Google Font API to import a new font, further details on licencing and use can be found at https://fonts.google.com/specimen/Play/about and at https://developers.google.com/fonts/docs/css2 
 
*HTML Set Up*

The initial Page Set Up has been defined in the Head and references the Character Set, Language and link to the CCS sheet.
 
*Navigation Bar*

For the Navigation Bar I have defined a Class of navbar, this is created in CSS sheet and has various other formatting added as below. My favourite is the a:hover class which enables a line under the list item when the user moves their cursor over it.

**Sprint Retro**
|What’s Gone Well      |What Could Have Been Better |
|----------------------|----------------------------|
|The Nav Bar creation, understanding how to remove ul formatting. |Learning to use of the a.hover class	-	Would like to apply a Hamburger Menu to the Nav Bar |



## Iteration Three ##
|Date	                |Aims & Objectives	         |Release       |
|---------------------|----------------------------|--------------|
|01/03/24 to 31/03/24	|Rich Media, Google Maps     |28/03/24     |
|                     |Images, video, YouTube | |
		
**Sprint Notes & Development Decisions**

Sprint three was all about media, images, and external content, I have identified and stored locally some static imagines for my website, these have been added to a library folder which will be included in the webserver. I have also research relative path addresses to better use the images.

*Font Awesome*

To begin with I was going to use library images for my social icons, however I had issues with resolution and also responsiveness, to overcome this I researched and found https://fontawesome.com/ which is a subscription based application which allow you to render images directly into you code using the Font Awesome API.
To enable this, I have added the following code, the HTML head SCR that allows access to Font Awesome. Then each HTML element is managed with in the i class where colours, size and links have been added.
 
*Google Maps*

I started by using the Google Maps API to render a responsive map into the HTML. On the About Broughton page I wanted to allow the user to explore the area and see local amenities like schools, shops and libraries etc.
However, this is a subscription services and I leveraged a 30 day trail to build my website which then expired. I moved away and used an embed code which is not as good but is free, frustrated as the API allowed me to create Pin Drops and leverage local business searches.
https://mapsplatform.google.com/ 
Anyway, still managed to add an embedded map using a container as below but with less functionality.

*YouTube Embedded*

I have embedded a media player in the History page, this allow a YouTube video that depicts the Vickers Aircraft factory. Similarly to the Maps feature this is using an iframe HTML code.
 
*Google Calendar*
I wanted a way to share an up-to-date list of events, staying with the Google theme I have chosen to use a public Google Calendar which is generated within my Personal Google Account.
I’m very pleased with this and have been able to render functionality in the iframe class to change colours to match my website styles. I have also included functionality that opens the users mail client to allow then to send an email to a predefined emails address.
 
**Sprint Retro**
|What’s Gone Well      |What Could Have Been Better |
|----------------------|----------------------------|
|Using Font Awesome to overcome the challenges I had with resizing Social Icons.|Had issues understanding how to resize Social Icons using Library Images.|
|The use of Google Calendar to share events.|Wanted to use Google Map but it’s a paid services and the trial expired.|
|Email Clients redirection from a button.	||


## Iteration Four ##
|Date	                |Aims & Objectives	         |Release       |
|---------------------|----------------------------|--------------|
|01/04/24 to 30/04/24	|Responsiveness              |25/04/24|
|                     |Accessibility, tags etc     | |
|                     |Multilingual                | |
	 	
**Sprint Notes & Development Decisions**

As I head into the final weeks of the project this sprint is very much about refinement, this includes reviewing Accessibility with the addition of Alt Tags and considerations on the site being Multilingual to meet the local demographic of being in Wales.

*Responsiveness*

I’ve worked towards making my website responsive and introduced the below code to my CSS styling.
      
*Accessibility*

Now that my code is stable and I’m happy with the website I have revisited my accessibility and used the WAVE browser extension.

*Multilingual*

I investigated the use of two index pages and was able to hold the translated HTML, however I have struggled with publishing two index pages to the webserver so have chosen to put this feature on holder due to time constraints.

**Sprint Retro**
|What’s Gone Well      |What Could Have Been Better |
|----------------------|----------------------------|
|Using WAVE to increase my Accessibility Score.|Multilingual, struggled to get the browser to respond to local languages so chose to park this feature due to time constraints.|
|                                              |The responsiveness of my menu and the resizing on some images.|


## Iteration Five ##
|Date	                |Aims & Objectives	         |Release       |
|---------------------|----------------------------|--------------|
|01/05/24 to 31/05/24	|HTML Testing                |30/05/24 |
|                     |CSS Testing                 | |
|                     |Deploy to LIVE environment  | |

**Sprint Notes & Development Decisions**

The final sprint was very much about testing, and I have also deployed my website to GitHub Pages, more details on testing can be found in the appendix 6. Test Cases and information about my live deployment with pull requests etc can be found in the appendix 5. The Use Of GitHub For This Project
The remainder was focused on completing my journal and finalising my assignment submissions.

*CSS Validator*

I took advantage of the W3 CSS validator, and the testing results and decisions can be found in the appendix CSS Validation

*HTML Mark Up Validation*

I took advantage of the W3 HTML validator, and the testing results and decisions can be found in the appendix HTML Validation

*Live Deployment*

I enjoyed finding a way to use GitHub to deploy my website, I have also been using GitHub to document my first years journey anyway so it was perfect in terms of continuity. Whilst I appreciate that Github can not be my journal I did start out by planning my Sprints and project in there as well.

https://github.com/tobybeevers/ICL-1321-Web-Technologies

https://github.com/users/tobybeevers/projects/2 

https://tobybeevers.github.io/ICL-1321-Web-Technologies/ 

**Sprint Retro**

|What’s Gone Well      |What Could Have Been Better |
|----------------------|----------------------------|
|Testing and deployment to GitHub Pages.|WAVE, I needed to go back through my coded and change some design choices|
|My CSS code choices made it easy to effectively change some of my design choices for the WAVE testing.||


## Conclusion ##
In conclusion, this portfolio chronicles the comprehensive journey of developing a small, accessible website enriched with multimedia content, adhering to valid HTML and CSS standards. The project was segmented into two key phases: initial design documentation and the practical implementation and journal maintenance. Throughout the development, a strong emphasis was placed on accessibility, ensuring the website is inclusive and user-friendly across various platforms and for users with disabilities.

The adoption of Agile principles, particularly a modified Scrum methodology, facilitated an iterative development process. Each sprint focused on specific aspects of the project, from foundational designs and accessibility considerations to the integration of rich media and final testing. The iterative nature allowed for continuous improvement and flexibility to adapt to changing requirements, ensuring the final product was robust and functional.

A significant part of the project involved thorough testing and validation. Utilising tools like the W3C validators for both CSS and HTML ensured code quality and standard compliance. 

Key achievements include the successful creation of a responsive and accessible navigation bar, integration of rich media such as Google Maps and YouTube videos, and the implementation of a public Google Calendar for event sharing. Challenges, such as the limitations of Google Maps' subscription service and difficulties with multilingual support, were acknowledged and addressed within the constraints of the project timeline.

The final deployment to GitHub Pages marked the culmination of the project, demonstrating the ability to translate initial designs into a functional, live website. The project not only highlights technical proficiency in web development but also underscores the importance of accessibility and user-centric design in creating digital platforms. This journey has been one of learning and adaptation, resulting in a website that is both accessible and engaging for its intended audience.
