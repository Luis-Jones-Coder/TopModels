![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

 
# THE DREAM MODEL >> Project

## Project Purpose

### General Objective
Develop a professional website for the modeling agency that effectively showcases models, previous work, and services offered, facilitating connections between potential clients and the agency.

### Technologies Used

[**Flexbox**](Flexbox)
- Flexbox makes it easy to create flexible and responsive layouts.

[**HTML5**](https://www.w3schools.com/html/html_intro.asp)
- Was used to structure the web page  

[**Google Fonts**](https://fonts.google.com/)
- Google font was used for the font of the website.

[**Custom CSS**](https://www.w3schools.com/css/)
- Was added to override default Bootstrap styles and match the client’s branding.

[**Fontawesome**](https://fontawesome.com/kits)
- Was added to add the icons in the page.

[**Bootstrap Framework**](https://getbootstrap.com/)

- The website utilizes the Bootstrap framework to ensure a responsive and modern design.

- Bootstrap CSS and JavaScript files were included in the project via CDN links

[**Custom CSS**](https://www.w3schools.com/css/)

- Was added to override default Bootstrap styles and match the client’s branding.


### [User Story](https://github.com/users/Luis-Jones-Coder/projects/4)
**1. Showcase Model Portfolio:** Provide a high-quality visual gallery that highlights models who have worked with the agency and previous projects.

**2. Facilitate Contact:** Include a contact form and key information sections (such as location and operating hours) so potential clients can easily get in touch with the agency.

**3. Describe Offered Services:** Clearly and concisely present the different modeling services available.

**4. Promote New Opportunities:** Inform aspiring models on how they can join the agency and the benefits and requirements involved.

### Target Audience

- **Potential Clients:** Individuals or companies looking to hire models for photo shoots, fashion shows, advertising campaigns, etc.

- **Aspiring Models:** Individuals interested in joining the modeling agency and developing their professional careers.

- **Collaborators and Media:** Professionals in the fashion and media industries interested in collaborating with the agency.
---
### Descriptions and Content
- Engaging descriptions of the agency's environment and types of modeling opportunities available were written and provided by the client.

- Content was reviewed and edited for clarity, conciseness, and SEO optimization.
- Descriptions were directly integrated into the website’s HTML.

### Tools Used
[**Flexbox**](Flexbox)
- Flexbox makes it easy to create flexible and responsive layouts.

[**HTML5**](https://www.w3schools.com/html/html_intro.asp)
- Was used to structure the web page  
[**Google Fonts**](https://fonts.google.com/)
- Google font was used for the font of the website.









### Deployment
**1. Code Review:** Ensured all code is clean, error-free, and well-documented.
### Local Testing:
**Issue Description: JOIN US** 
The "JOIN US" button, located at the top-right of the page, presented a visual error during mouse hover in the Gallery section and the Form section. When hovering over the button:

- The background color changed to white, but the text color did not adjust accordingly.

- This caused the button's text to become invisible, making it unreadable and disrupting the user experience.

**Root Cause Analysis:**
Both the Gallery section and the Form section had a CSS class named text-white.

This class forced the text color to turn white on mouse hover, regardless of the button's background color.

As a result, the content of the button became indistinguishable.
**Resolution:**
The issue was resolved by removing the text-white class from the sections that caused the conflict.

**Before Fix:**
Hovering over the "JOIN US" button changed its background to white while keeping the text color white, rendering the text invisible.

The issue was consistently observed in both the Gallery and Form sections.

**After Fix:**
After removing the text-white class, the button text color now remains visible during hover.

The button functions correctly, maintaining good contrast between the background and text.

**Test Report: Navigation Bug on Small Screens**

**Issue Description:**
The navigation bar was not functioning properly on small screens. The issue was caused by the hero image, which affected the usability of the navigation bar by making it difficult to interact with on smaller devices.

**Root Cause Analysis:**
The hero image did not adapt well to smaller screen sizes, causing layout conflicts and obstructing the navigation bar.

This made the navigation experience cumbersome and non-responsive.

**Resolution:**
The problem was resolved by adding the col-12 class to the hero image section.

This ensured that the hero image properly spans the width of the screen on smaller devices, improving the layout and usability.

**Testing Results:**

**Before Fix:**
Navigation bar was obstructed or unresponsive on small screens.

User interactions with the navigation bar were inconsistent and frustrating.

**After Fix:**
Navigation bar is now fully functional on small screens.

The layout adjusts seamlessly, and the hero image no longer interferes with navigation.

Conclusion:
The issue with the navigation bar has been successfully resolved. Adding the col-12 class ensures a responsive and user-friendly interface across devices, significantly improving the overall user experience.

**HTML validator WRC**
I have used the recommended css [validator WRC](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate all of my css files.

**CSS validator WRC**
I have used the recommended html [validator WRC](https://validator.w3.org/#validate_by_input) to validate all of my html files.



Functional Testing: Tested all critical functionalities (forms,links, responsive fuctionality) to confirm they work as expected.

Monitoring: Set up monitoring tools to ensure the site is available and functioning correctly at all times (e.g., Google Analytics, UptimeRobot).

## Acknowledgements

- [**Pixabay:**](https://pixabay.com/) For providing high-quality, free stock images.
- [**Bootstrap:**](https://getbootstrap.com/) For offering a robust framework that simplifies the development of responsive websites.
- [**Fontawesome:**](https://fontawesome.com/kits) The extensive library of icons and the ease of integration significantly enhanced the visual appeal and functionality of our site.
- [**Google Fonts**](https://fonts.google.com/) For providing an amazing collection of fonts that made our website look stunning and professional
