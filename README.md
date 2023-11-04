# Welcome to "Taste of Bulgaria" - A Culinary Journey
  
 "Taste of Bulgaria" is more than just a restaurant, it's a culinary journey into the heart of Bulgaria. The project is intended for food enthusiasts, adventurers, and anyone seeking a unique and delightful dining experience. "Taste of Bulgaria," offers not just meals but memories. The project is designed to introduce all food lovers to the tastes and aromas of Bulgaria, ensuring that each dish bursts with authentic flavor.
 
 ![Final project image home page](assets/docs/responsive-test.PNG)

 Visit the deployed site: [Taste of Bulgaria](https://desideneva.github.io/taste-of-bulgaria/)

 ## Existing Features

###  _Navigation Bar_

- Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Join Us page and is identical in each page to allow for easy navigation.

- This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![Nav Bar](assets/docs/header.PNG)

### _The landing page image_

- The landing includes a photograph that grab user`s attention on a few of the most well known traditional Bulgarian dishes in a typical traditional environment.

![Landing Page](assets/images/food-hero.webp)

### _Announcement section_

- This section was designed to keep users informed about the grand opening of a new Bulgarian restaurant.

![Announcement section](assets/docs/announcement.PNG)

### _Menu Section_ 

- A specially designed menu for the opening day,  bursting with authentic flavor, takes the user through Bulgaria's regions, from the Rhodope Mountains to the Black Sea coast.

![Menu section](assets/docs/menu.PNG)

### _Welcome Section_

- This section allows the user to see exactly when the opening  will happen, the exact location, and the time.

- The image on the side captures the essence of the restaurant – a warm, genuine, and welcoming atmosphere. The smiling female adorned in a traditional Bulgarian costume embodies the friendliness and warmth that awaits the user.

![Welcome section](assets/docs/welcome-image.PNG)

### _The Footer_

- The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user.

- The footer is valuable to the user as it encourages them to keep connected via social media.

![Footer](assets/docs/footer.PNG)

### _Gallery_

- The gallery will provide the user with supporting images to see what the restaurant and some of the meals look like.

- The gallery provides users with a visually appealing experience and adds significant value by offering a visual, culinary, and cultural experience to users. 

![Gallery page](assets/docs/gallery.PNG)

### _The Join Us Page_

-  Users are encouraged to engage with the restaurant by taking action on the "Join Us" page. Whether it's making a reservation, signing up for updates, or reaching out, this engagement builds a stronger connection between the user and the restaurant. The user will be asked to submit their full name and email address.

![Join Us page](assets/docs/join-us.PNG)

### _Features Left to Implement_

- Main Page Slideshow: Enhance the main page by adding an engaging image slideshow. This dynamic element will provide an eye-catching visual experience for the users.

- Gallery Page Videos: Enrich the Gallery page by incorporating short videos from various events, such as folklore evenings, engagement parties, and kids' parties. These videos will give users an immersive glimpse into the vibrant atmosphere and experiences offered at the restaurant.

- Discount Popup on Join Us: Upon signing up on the "Join Us" page, implement a feature where a welcoming message with a 10% discount offer for the first booking pops up. This tempting promotion will encourage users to take immediate action, making it even more motivating to join an event at the restaurant or savor its delicious meals with family and friends.
 
These forthcoming features will make the website more interactive, captivating, and appealing to a broader audience, ultimately enhancing the user experience and encouraging participation in the restaurant's events and culinary delights.

## Solved Bugs

- Navbar Toggle: The toggle for the navbar appeared under the heading instead of next to it due to a spelling mistake in the CSS. "position: absolute" was applied incorrectly, missing the "e" at the end.

- Spelling Mistake: Another spelling mistake had a significant impact on the navbar. "a: hoover;" was used instead of "a: hover;" in the CSS, causing unintended behavior.

- Image Size Issue: Three images for the main page were of different sizes, and efforts to compress and resize them were ineffective. As a solution, the idea was changed, and a "Welcome" section was created instead, which resolved the issue.

- Media Query Issue: When applying the "Form" section under a media query, it unintentionally prevented the background image from appearing on the "Join Us" page, leading to an unexpected display problem.

- Bracket Closing Mistake: Forgetting to close a bracket resulted in various unintended consequences, such as the text not appearing on the screen, the color changing unexpectedly, the text font altering, or text alignment issues. Identifying and resolving these bracket-related bugs was time-consuming.

These experiences highlight the importance of thorough testing and attention to detail during project development.
## Testing

Every aspect of the project was tested on the browsers below.

![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)
![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)

### _User Testing_

- The navigation menu needs to be simple to use on a range of devices, including desktop, tablet and mobile.

  - The navigation bar is visible on all pages with an indicator to show which page the user is on.
  - The navigation bar is easy to read and easy to understand what each button does.

- Maneuvering around the site should be simple and straightforward  

  - Everything is laid out in a clear manner that is simple to use.
  - The navigation bar is clear and visible at the top of each page.

- The images should be clear and not stretched or squashed

  - All images are visibly clear on all pages.

### _Styling and Layout_

| Expected    | Result |
| :---------: | :----: |
| Ensure images loads correctly and functioning as expected | Pass |
| Ensure all images loads correctly | Pass |
| Ensure all backgrounds images load correctly | Pass |
| Ensure main page header loads correctly | Pass |

### _Responsiveness_

| Page | Images and Content Responsive | Text Content Readable    |
| :--: |:----------------------------: | :----------------------: |
| Home Page | Pass | Pass |
| Gallery Page | Pass | Pass |
| Join Us Page | Pass | Pass |

### _Code Validators_

The W3C Markup and CSS Validators were used to validate my project to make sure there were no errors within the site. 

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

 - Home page
 ![HTML Home page test](assets/docs/html-home-page-test.PNG)

 - Gallery page
 ![HTML Gallery page test](assets/docs/html-gallery-page-test.PNG)

 - Join Us page
 ![HTML Join Us page test](assets/docs/html-joinus-page-test.PNG)


![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
  
   ![CSS test](assets/docs/test-css.PNG)

### _Lighthouse Testing_ 

- Desktop

![Hope page results](assets/docs/desktop-home-perf.PNG)

![Gallery page results](assets/docs/desktop-gallery-perf.PNG)

![Join Us page results](assets/docs/desktop-joinus-perf.PNG)

- Mobile

![Home page results](assets/docs/mob-home-perf.PNG)

![Gallery page results](assets/docs/mob-gallery-perf.PNG)

![Join Us page results](assets/docs/mob-joinus-perf.PNG)

#### Performance

- I was very happy with my initial lighthouse scores.
- The issues reducing my performance scores are that I have a large size images, including background images.
- My mobile scores are lower due to the scaling down of images and text for use on mobile.

#### Accessibility

- While writing my code, I was careful to ensure that it was fully accessible.
- All text has good visibility on the background I chose.

#### Best Practices

- All images are shown in the correct aspect ratio, so as not to look stretched or pixelated.

#### SEO

* I ensured the site had all the relevant meta tags needed.
* All font sizes are legible on all screen sizes.





 


 








 


 