# Week-2-Portfolio

Week Two Challenge of the *UOB Full Stack Development Coding Bootcamp* requires students to develop a portfolio to showcase work samples.

We were given an Acceptance Criteria as per below:

Acceptance Criteria:

![Acceptance Criteria](./assets/images/acceptance-crit.png) 

I approached this task by first creating a wireframe on Adobe InDesign to ensure that I am meeting the points as listed above, and to clearly map out what elements are required:

![Wireframe](./assets/images/wireframe.png) 

## Screenshot of Application:

![Home](./assets/images/home.png)

* When the portfolio is loaded, you are presented a navigation bar at the top of the page with working links which scrolls to the different sections - About, Portfolio, Experience and Contact. 

* There is also a recent photo, name and a contact button which is linked to the Contact form. 

![About](./assets/images/about.png) 
![Featured Project](./assets/images/mainproj.png) 
![Other Projects](./assets/images/project.png)

* In the Portfolio section, you are presented with a **Featured Project** and placeholders for **six** further projects. 

* The Featured *'Baxters'* Project image is also larger in size comparison to the other projects, and when clicked, will take you to the deployed application. 

![Contact Form](./assets/images/contact.png) 

* The bottom of the page includes a Contact Form and a Footer allowing visitors to easily get in touch either by submitting a form, or through a social link i.e LinkedIn.  


## Using Media Queries to create a responsive layout:

<img src="./assets/images/mobile_nav.png" alt="Responsive Nav Bar" width="320"/>
<img src="./assets/images/mobile_proj.png" alt="Responsive Project Section" width="310"/>

```
@media screen and (max-width: 768px) {
    .container,
    .flex-item-2,
    #intro {
        flex-direction: column;
        display: block;
        text-align: center;
        margin: 0 auto;
        position: static;
    }
```

* It's also important to create a responsive layout that adapts to different viewports to improve the user experience and enhance interactions. Above is a section of my code in *style.css*. For viewports of 768px and under, the flex-direction changes to columns instead of rows.

## URL to Deployed Application:

#### Final note: 

*As always, any feedback for improvements would be appreciated* 😊



