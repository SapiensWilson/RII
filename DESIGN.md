# Richardson Industries Website Design

## Introduction

The Richardson Industries website was created to provide an online presence for the company, showcasing its services, team members, and pricing models. 
The primary goal of the website is to offer information about the company and its offerings, while also enabling potential clients to get in touch through a contact form.

## Technologies Used

The website was built using the following technologies:

- HTML5 for structuring the content
- CSS3 for styling and layout
- JavaScript for handling the contact form submission
- Bootstrap 5 framework for responsive design and pre-built components

## Website Structure

The website follows a single-page design, with the following sections:

- Home: A hero section with a brief introduction and a call-to-action button
- About: An overview of the company and its mission
- Services: A list of services offered by the company
- Team: Profiles of key team members
- Pricing: Different pricing models and their benefits
- Contact: A contact form for users to get in touch with the company

The files and folders are organized as follows:

- index.html: The main HTML file
- assets: A folder containing all the assets for the website, including:
  - css: Folder containing the style.css file
  - img: Folder containing all the images used on the website

## Layout and Styling

The website's layout and styling were primarily achieved using the Bootstrap 5 framework. 
Pre-built components such as the navigation bar, cards, and grid system were customized to fit the website's design requirements.

Additionally, a custom CSS file (style.css) was created to further modify the styles and override some of the Bootstrap defaults. 
This file includes customizations for elements such as colors, typography, and spacing.

## Responsive Design

To ensure that the website is accessible on various devices, responsive design principles were followed throughout the development process. 
The Bootstrap 5 framework provides responsive utility classes and a grid system that automatically adapts the layout to different screen sizes.

Custom media queries were also added in the style.css file to fine-tune the website's appearance on different devices and ensure an optimal user experience.

## Challenges and Design Decisions

During the development of the website, a few challenges were encountered:

1. **Image sizing**: Some of the team member images had different dimensions, causing inconsistencies in the layout. This issue was resolved by resizing the images to have consistent dimensions and using CSS to maintain aspect ratios.

2. **Pricing section**: The Hourly Rates pricing box was shorter than the others, leading to a misaligned layout. To fix this issue, a min-height was set for the boxes to ensure they all have the same height. 
[May 7th 13:50 - Just now realized an issue with the pricing boxes still persists with the changing of window sizes :\ ]

3. **Typography**: To emphasize the Hourly Rates price, the font size was increased using CSS to make the text more prominent.

4. **Contact Form** : The orginal contact form was useful but for the longevity of the website a 3rd party app was installed Formspree so that different emails could be swapped as the recipeint easily without having to modify source code.

Throughout the project, design decisions were made to ensure a clean and professional look while maintaining a user-friendly interface. The choice of colors, typography, and layout was made with the company's brand identity and target audience in mind.
