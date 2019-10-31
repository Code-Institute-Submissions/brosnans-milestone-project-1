# Milestone Project - Powerhouse Gym

*Developer: Seaghan Brosnan*

- [Project Brief](#project-brief)
- [Technologies](#technologies-and-dependencies)
- [UXD](#uxd)
- [Wireframes](#wireframes)
- [Deployment](#deployed-to-github-pages)
- [Tests and Fixes](#tests-and-fixes)

### Project Brief

In this project, you’ll be building a frontend-only website using the technologies that you have learned throughout User Centric Frontend Development.

Build a static (front-end only) website for a gym - The Powerhouse Gym. As a starting point, you may want to use wireframes, as we did in the UX lesson.

The gym has been in business for just over one year. You have been given the following requirements after interviews with the client’s representatives:

- Their primary target audience are adults in the surrounding area interested in their personal fitness.

- They would like to use the site to showcase the positive experiences of their members and their flexible class timetables.

- They would like a facility where prospective members can request a consultation with a professional from the gym.

- They are in the process of creating a social media presence and would like to add links to their social media pages.

### Technologies and Dependencies

- HTML5
- CSS3
- Bootstrap v3.3.7
- - https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
- - https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js
- Font Awesome v4.7.0
- - https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css

### UXD

| Strategy  | Focus                                                       | User Needs                                                                                        | Business Objectives                                                                             |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
|           | What are you aiming to achieve?                             | I’m interested in personal fitness and want to find out more about the gym’s facilities           | Increase clients                                                                                |
|           |                                                             | I want to find out current members experience of the gym                                          | Social currency                                                                                 |
|           | For whom?                                                   | I want to book a consultation with a professional from the gym                                    | Increase brand awareness                                                                        |
|           |                                                             | I want to read about the current members experience                                               |                                                                                                 |
|           | Target Audience?                                            | I want to see what classes run and on which days                                                  |                                                                                                 |



| Scope     | Focus                                                       | Functional Specification                                                                          | Content Requirements                                                                             |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|           | Which features?                                             | Home                                                                                              | Get an overview of the gyms member experiences                                                   |
|           | What’s on the table?                                        | Timetables                                                                                        | View the gyms class timetables                                                                   |
|           |                                                             | Contact Us                                                                                        | Book a consultation                                                                              |
|           |                                                             | Download                                                                                          | Download a copy of the class timetables                                                          |
|           |                                                             | Social                                                                                            | Access links to social media                                                                     |



| Structure | Focus                                                       | Interaction Design                                                                                | Information Architecture                                                                        |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
|           | How is the information structured?                          | Where am I? / How did I get here? / What can I do here? / Where can I go?                         | Organizational / Navigational schemas (dashboard)                                               |
|           |                                                             |                                                                                                   | Home - member testimonials                                                                      |
|           | How is it logically grouped?                                | Mobile - fixed navbar                                                                             | Timetables - class timetables                                                                   |
|           |                                                             | Desktop - fixed navbar                                                                            | Contact Us - book a consultation                                                                |



| Skeleton  | Focus                                                       | Interface Design                                                                                  | Navigational Design | Information Design |
|-----------|-------------------------------------------------------------|---------------------------------------------------------------------------------------------------|---------------------|--------------------|                    
|           | How will the information be represented?                    | See wireframes                                                                                    | Home                |                    |                                                    
|           |                                                             |                                                                                                   | Timetabes           |                    |                   
|           | How will the user navigate to the information and features? | Mobile - home / contact / timetables / in navbar                                                  | Contact Us          |                    |                                      



| Surface   | Focus                                                       | Visual Design
|-----------|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
|           | What will the finished product look like?                   | Fonts: @import url('https://brosnans.github.io/milestone-project-1/assets/CSS/style.css');                       |
|           |                                                             | 6c00bf                                                                                                               |
|           | What colours, typography and design elements will be used?  | ff7e40                                                                                                               |
|           |                                                             | eb7d34                                                                                                               |

#### Wireframes

https://github.com/brosnans/milestone-project-1/blob/master/assets/wireframe%20%231.JPG

https://github.com/brosnans/milestone-project-1/blob/master/assets/wireframe%20%232.JPG?raw=true

https://github.com/brosnans/milestone-project-1/blob/master/assets/wireframe%20%233.JPG?raw=true

https://github.com/brosnans/milestone-project-1/blob/master/assets/wireframe%20%234.JPG?raw=true

### Deployed to Github Pages

- Project repository: https://github.com/brosnans/milestone-project-1
- Project link: [https://github.com/brosnans/milestone-project-1](https://brosnans.github.io/milestone-project-1/index.html)
- Go to project repo settings on Github
- Select master branch and click save

### Tests and Fixes

[**HTML Validator Results**](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbrosnans.github.io%2Fmilestone-project-1%2Findex.html)

[**CSS Validator Results**](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbrosnans.github.io%2Fmilestone-project-1%2Fassets%2FCSS%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

#### *Mobile*

Tested on iPhone 5, 6, 7, 8 and X

**PROBLEM**

Navbar in two lines

**FIX**

Added media query to make navbar responsive in mobile view

```css
@media (min-width: 600px) {
  .top-navbar {
  
}
}

@media (max-width: 600px) {
  .top-navbar {
  display: grid
}
}
```

---


#### *Desktop*

Tested on Chrome, Safari, Firefox
