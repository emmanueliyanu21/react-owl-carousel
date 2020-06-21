Create ReactJS Project
Let's first create a React application using the following command:

npx create-react-app matform 

Open the newly-created project in Visual Studio Code and Install bootstrap in this project by using the following command:

npm install --save bootstrap 

Now, open the index.js file and import Bootstrap:

import 'bootstrap/dist/css/bootstrap.min.css'; 

Install Owl Carousel
Now install Owl Carousel by using the following command:

npm install react-owl-carousel --save

Now open index.html, add jquery reference, add the following line in head

<script src="https:code.jquery.com/jquery-3.4.1min.js"></script>

Now go to src folder and create a new component 'Owldemo1.js' and add the following reference in this component

import OwlCarousel from 'react-owl-carousel';  
import 'owl.carousel/dist/assets/owl.carousel.css';  
import 'owl.carousel/dist/assets/owl.theme.default.css';