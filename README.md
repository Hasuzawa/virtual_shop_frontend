# Project: Virtual Shop
This is the frontend of a virtual shop project. There is <b>no</b> actual transaction involving real money.

[The deployed version]()<br>
[The backend of this project](https://github.com/Hasuzawa/virtual_shop_backend)

## This project features:
[Features implemented in past projects]() are omitted for brevity.
<ul>
    <li>more advanced React features: hooks, ref, portal</li>
    <li>more refined responsive design (3-phrases)</li>
    <li>drag & drop events</li>
    <li>async request to server</li>
</ul>


# Techs used
<details open>
    <summary>Programming languages & frameworks</summary>

<img src="./public/logos/Typescript_logo.svg" alt="TypeScript" width="70" height="70">
<img src="./public/logos/React_logo.svg" alt="React" width="70" height="70">
<img src="./public/logos/HTML_logo.svg" alt="HTML" width="70" height="70">
<img src="./public/logos/CSS_logo.svg" alt="CSS" width="70" height="70">
<img src="./public/logos/Bootstrap_logo.svg" alt="Bootstrap" width="80" height="70">
<img src="./public/logos/Sass_logo.svg" alt="Sass" width="70" height="70">
<img src="./public/logos/GraphQL_logo.svg" alt="GraphQL" width="70" height="70">
<img src="./public/logos/Apollo_logo.svg" alt="Apollo" width="130">
</details>

## some technical background
<details close>
<summary>design choice</summary>

<ul>
<li>
    In the last project I used JavaScript for React, but there were numerous issues such as lack of 
    enum, and unpredictable behaviour in function parameter. Therefore, I use TypeScript for this project.
    I place focus on simplicity and clarity of structure, and do not aim to provide the most feature in this project.
</li>
<li>
    I used more functional component and hook than the previous project. React does not really have inheritance so class method
    is not reusable across component. Hooks however can.
</li>
<li>
    The drag drop event. Drag drop event is a vulnerability because of potential cross-site dropping. In a real app a lot of sanitisation has to be done. I took another approach and 
    make a class. An instance is dragged and only that instance will be processed in drop event. This will not prevent all abuse but that is the
    job of backend, not frontend.
</li>
<li>
    GraphQL and Apollo API. This is one of the major motive of this project. Rest API is a more
    mature technology but it is time to move on to newer
    frameworks.
</li>
<li>
    I am in fact using both Windows and MacOS and there is subtle differences of the website even on the same browser.
</li>
</ul>
</details>