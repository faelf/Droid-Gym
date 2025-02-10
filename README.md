# Droid Gym
This webpage was developed for the Milestone 1, focusing on creating an engaging and functional website for a gym. The design aims to provide an intuitive user experience, featuring essential information such as class timetables, gallery and contact details. The website has a responsive design, and interactive elements to ensure accessibility across different devices.

![Desktop Screenshot](/assets/readme/multi-device-screenshot.png)

## Table of Contents
1. [User Stories](#user-stories)
2. [Wireframes](#wireframes)
3. [Features](#features)  
3.1 [Existing Features](#existing-features)  
3.2 [Features Left to Implement](#features-left-to-implement)
4. [Technologies Used](#technologies-used)
5. [Deployment](#deployment)
6. [Testing](#testing)
7. [Credits](#credits)

## User Stories
- As a gym member, I want to check the class timetable.
- As a potential gym member, I want to see what the gym offers.
- As a potential client, I want to see high-quality images of the gym
- As a new user, I want to find the gym’s contact details easily so that I can enquire about services.
- As a mobile user, I want the webpage to be responsive, and I want to book a session online.
- As a first-time visitor, I want to see testimonials from existing members.
- As a social media user, I want to stay updated on events and news.

[Back to the top](#table-of-contents)

## Wireframes



[Back to the top](#table-of-contents)

## Features
### Existing Features
- Navigation bar. Responsive to be accessible on any screen size.
![Navigation Menu](/assets/readme/features/navigation-bar.png)

- Join Us! Section. For new and returning customers to be able to book classes on the go.
![Booking Form](/assets/readme/features/booking-form.png)

- Classes timetable. For users to check when the classes are available.
![Timetable](/assets/readme/features/classes-timetable.png)

- Gallery. So people can see the facilities.
![Gallery of photos](/assets/readme/features/photo-gallery.png)

- Thank you page after submitting a request. To offer feedback to the customer.
![Submition page](/assets/readme/features/thank-you-page.png)

- Footer containing social links, and address. For customers to be able to keep up to date with information, and see where the gym is.
![Footer information](/assets/readme/features/footer.png)

### Features Left to Implement
- Dark mode.
- Payment through the webpage.
- User log in to see payment history.
- Shop selling gym clothes.

[Back to the top](#table-of-contents)

## Technologies Used
### Languages Used
- HTML
- CSS

### Frameworks, Libraries & Programs Used
- Bootstrap
- Google Fonts
- GitHub
- VS Code
- [Favicon Generator](https://favicon.io/emoji-favicons/)
- [Image Converter](https://www.freeconvert.com/)
- [Colour Picker](https://www.webfx.com/web-design/color-picker/)

[Back to the top](#table-of-contents)

## Deployment

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

1. I created a public repository.
2. Logged into Github.
3. From the list of repositories I selected the repository.
4. Navigated to the Settings tab.
5. On the left menu went to Pages.
6. Chose the main branch for deployment, and clicked on save.
7. On the code tab, clicked on the engine icon next to about.
8. Under the website input, checked the option Use your GitHub Pages website.
9. Saved the changes, and the link to the deployed webpage should appeared.

This is the [link](https://faelf.github.io/Droid-Gym/) to the live page.

[Back to the top](#table-of-contents)

## Testing

- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input)
- Google Chrome Lighthouse in Developer's Tools

### Bugs
#### Testing The Deployed Page
- The links weren't working, and checking the HTML, I had misspelled the path.

#### Testing on the W3C Markup Validation
- After running the W3C Markup Validation, there was a H2 tag missing in the Gallery Section.
![W3C Validation Result Screenshot](/assets/readme/w3c_validation/w3c-html-validation.png)
Add a H2 tag with a class Hidden, and this was the result
![No errors message](/assets/readme/w3c_validation/no-errors.png)

#### Testing on the W3C CSS Validation
- There was no errors found.
![Screenshot of W3C CSS Validation](/assets/readme/w3c_validation/w3c-css-validation.png)

#### Testing Using Lighthouse
- These were the results of the lighthouse:
![Index Accessibility](/assets/readme/b-index-accessibility.png)
![Index BP](/assets/readme/b-index-bp.png)

- On the other pages I had the same results. And these are the results after fixing the bugs.

![Index After](/assets/readme/a-index.png)
![Classes After](/assets/readme/a-classes.png)
![Gallery After](/assets/readme/a-gallery.png)
![Join After](/assets/readme/a-join.png)
![Thank you After](/assets/readme/a-thankyou.png)

#### Testing the deployed page on PageSpeed
- Testing the index.html
    - Mobile
    ![index.html pagespeed results image](/assets/readme/pagespeed/b-mobile-index.png)
        - Best Practices Message
        ![index.html message best practices message image](/assets/readme/pagespeed/b-mobile-index-msg-1.png)

    - Desktop
    ![index.html](/assets/readme/pagespeed/b-desktop-index.png)

- Testing the classes.html
    - Mobile
    ![classes.html pagespeed results image](/assets/readme/pagespeed/b-mobile-classes.png)
    - Desktop
    ![classes.html pagespeed results image](/assets/readme/pagespeed/b-desktop-classes.png)

- Testing the gallery.html
    - Mobile
    ![gallery.html pagespeed results image](/assets/readme/pagespeed/b-mobile-gallery.png)
        - Accessibility Warning
        ![gallery message 1](/assets/readme/pagespeed/b-mobile-gallery-msg-1.png)
    - Desktop
    ![gallery.html pagespeed results image](/assets/readme/pagespeed/b-desktop-gallery.png)
        - The same message result, 'Heading elements are not in a sequentially-descending order.'.
    
- Testing the join.html
    - Mobile
    ![join.html pagespeed results image](/assets/readme/pagespeed/b-mobile-join.png)
        - Accessibility Warning
        ![join.html accessibility message image](/assets/readme/pagespeed/b-mobile-join-msg-1.png)
    - Desktop
    ![join.html](/assets/readme/pagespeed/b-desktop-join.png)
        - The same message result, 'Heading elements are not in a sequentially-descending order.'.

- Testing the thank-you.html
    - Mobile
    ![thank-you.html pagespeed results image](/assets/readme/pagespeed/b-mobile-thank-you.png)
        - Accessibility Warning
        ![thank-you.html accessibility message image](/assets/readme/pagespeed/b-mobile-thank-you-msg-1.png)
    - Desktop
    ![thank-you.html pagespeed results image](/assets/readme/pagespeed/b-desktop-thank-you.png)
        - The same message result, 'Heading elements are not in a sequentially-descending order.'.

After some considaration, I have decided to keep the quality of the images as they were on the index.html. And fixed the accessibility headings, and the results were:

- Testing the gallery.html
    - Mobile
    ![last results on pagespeed](/assets/readme/pagespeed/a-mobile-gallery.png)
    - Desktop
    ![last results on pagespeed](/assets/readme/pagespeed/a-desktop-gallery.png)

- Testing the join.html
    - Mobile
    ![last results on pagespeed](/assets/readme/pagespeed/a-mobile-join.png)
    - Desktop
    ![last results on pagespeed](/assets/readme/pagespeed/a-desktop-join.png)

- Testing the thank-you.html
    - Mobile
    ![last results on pagespeed](/assets/readme/pagespeed/a-mobile-thank-you.png)
    - Desktop
    ![last results on pagespeed](/assets/readme/pagespeed/a-desktop-thank-you.png)

[Back to the top](#table-of-contents)

## Credits
The images were taken from the pages below:
- Class-boxing.webp - from Pixabay post on Pexels.
- Class-jj.webp - from RDNE Stock project on Pexels.
- Class-pt.webp - from Bruno Bueno on Pexels.
- Class-yoga - from Andrea Piacquadio on Pexels.
- Hero.webp - from Victor Freitas on Pexels.
- Gallery-1.webp - from Li Sun on Pexels.
- Gallery-2.webp - from Bruno Bueno on Pexels.
- Gallery-3.webp - from Cesar Galeao on Pexels.
- Gallery-4.webp - from Cesar Galeao on Pexels.
- Gallery-5.webp - from Cotton Studio on Pexels.
- Gallery-6.webp - from Cotton Studio on Pexels.
- Gallery-7.webp - from Leon Ardho on Pexels.
- Gallery-8.webp - from Andrea Piacquadio on Pexels.
- Gallery-9.webp - from Pixabay on Pexels.
- Gallery-10.webp - from Sabel Blanco on Pexels.
- Gallery-11.webp - from Scott Webb on Pexels.
- Gallery-12.webp - from Victor Freitas on Pexels.
- Testemonials pictures were created by ChatGPT.
- ChatGPT for text content.

[Back to the top](#table-of-contents)

