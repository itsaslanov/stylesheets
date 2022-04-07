# Structuring Sass projects with partials
- This divides 2 parts, 
- first approach is for small projects such as a single web page, landing page etc...
- as far as second one goes is for big projects like blog sites, news sites and such a kind of projects.
## why do you need?
Well, this makes your stylesheets more organized, readable and even a piece of cake to follow for any front-end developers. 
If you don't trust in, try for free. It is absolutely friendly open-source, so feel free to use in your project :fire:
## First approach
<img src="https://user-images.githubusercontent.com/95647896/162183149-5029fc79-0839-47d1-b454-a8236967210b.png" width="70%">
As you can see the picture, which shows the path of the stylesheet, is pretty clear to follow right? <br/>
- Here we have 3 partials connecting up to our main.scss. <br/>
- Base: contained within this file are all your resets, variables, mixins, and any utility classes. <br/>
- Layout: contains all the CSS that handles the layout, such as the container and any grid systems. <br/>
- Components: anything reusable such as buttons, navbars, cards etc. <br/>
- Main: it should ONLY contain the imports for the above files. <br/><br/>

`NOTE` in this repo, only stylesheets, in which are used for big projects, exist. Hence, just do it on your own <br/>
Create folder called whatever you want, but stylesheets sound like cool. Right After, inside of that folder, just add 3 partials as the picture shows <br/>

However, when we’re working on a larger project, we’ll need a more rigorous architecture, which we’ll look at in the below :fire:

## Second approach
The architecture known as the 7–1 pattern (7 folders, 1 file), is a widely-adopted structure that serves as a basis for large projects. You have all your partials organized into 7 different folders, and a single file sits at the root level (usually named main.scss) to handle the imports — which is the file you compile into CSS. 

<br/>

Here’s a sample 7–1 directory structure, I’ve included some examples of files that would sit inside of each folder:

First of all, just check this out what is going on inside of the stylesheets folder by seeing below the pic  :point_down:

<img src="https://user-images.githubusercontent.com/95647896/162169281-f7dc96b1-e297-485d-8f78-9d8d5e5bd721.png" width="70%">

