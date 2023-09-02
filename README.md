<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/adamsissoko/CS470">
    <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Logo" width="210">
  </a>

  <h3 align="center">CS 470: Full Stack Development II</h3>

  <p align="center">
    Adam Sissoko
    <br />
    <a href="https://github.com/adamsissoko/CS470/tree/main/documents/Docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="http://adamsissokobucket.s3-website-us-east-1.amazonaws.com/">View Demo</a>
    ·
    <a href="https://github.com/adamsissoko/CS470/issues">Report Bug</a>
    ·
    <a href="https://github.com/adamsissoko/CS470/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-course">About The Course</a></li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#how-i-developed-the-project">How I Developed The Project</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<div align="center">
  <h1>AWS Web Application for Resource Management</h1>
  <img src="https://github.com/adamsissoko/CS470/blob/main/images/main_page.png" alt="Main Application Interface" width="500">
</div>
<h2>Overview</h2>
<p>
  This repository showcases a containerized web application initially designed using Docker and Docker Compose for local development. The application features a front-end developed in Angular, a back-end implemented in Node.js, and utilizes MongoDB for initial data storage.The project later transitioned to the Amazon Web Services (AWS) infrastructure, taking advantage of the AWS service stack. The database was migrated to DynamoDB, and AWS Lambda functions were utilized for data processing and to enrich user interaction.</p>
<h3>Challenges and Learning Outcomes</h3>
<p>
  Maneuvering through AWS's complex configurations, especially between Lambda functions and the API Gateway, proved to be a labyrinthine task. The project necessitated rigorous debugging and troubleshooting efforts. This experience not only enriched my understanding of AWS but also allowed me to further develop my problem-solving skills. The application is now live and can be accessed via the link above.
</p>
<p align="right">(<a href="#readme-top">back to top</a>)</p><h2>Technological Stack</h2>
<p>
  This application was built using a robust stack of technologies, each contributing significantly to different facets of the application. For more information on how to run the application locally, please refer to the <a href="#installation">installation</a> section below.
</p>
<div align="left">: Used for crafting the responsive and intuitive front-end.: Serves as the back-end runtime, built on Chrome's V8 JavaScript engine.: A Node.js web application framework that handles the application's API and middleware.: Utilized for local data storage before migration to AWS DynamoDB.: Used for containerizing the application, enhancing its portability.: AWS's NoSQL database service, utilized for efficient data storage.: Serverless compute service, used for running backend functions in the AWS cloud.</div>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DEVLOPMENT OF THE PROJECT -->
### How I Developed The Project

<p>
This project was developed over a span of seven weeks and involved setting up containers for local development initially. To accelerate the development process, a pre-configured Angular application was employed, which can be found <a href="https://github.com/AngularTemplates/learn-angular-from-scratch-step-by-step">here</a>. Similarly, a pre-built API was utilized, accessible <a href="https://github.com/AngularTemplates/learn-how-to-build-a-mean-stack-application">here</a>. These foundations allowed more focus on integrating the various components and debugging.
</p>
<p>
The approach to this project was deliberate, emphasizing a detailed understanding of the tools at hand. Initially developed with Docker and Docker Compose, the application used Angular for the front end and Node.js for the back end, with MongoDB for local data storage. As the project progressed, it was migrated to Amazon Web Services, using DynamoDB for data storage and Lambda functions for handling data streams and user interactions. This transition required careful debugging due to AWS's specific requirements for Lambda function and API interactions.
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To install and run the local instance of this application on your own machine, you'll need to install Docker Desktop (Windows). You will also need to be running an IDE such as Visual Studio Code or similar.

### Prerequisites

Start by ensuring you have npm installed on your machine.

  ```sh
  npm install npm@latest -g
  ```
  
Get Docker Desktop <a href="https://www.docker.com/products/docker-desktop/">here</a>.

### Installation

To install and run the application, follow the instructions below.

1. Follow the <a href="https://github.com/adamsissoko/CS470/blob/main/documents/Guides/CS%20470%20Module%20One%20Assignment%20-%20Docker%20Containers%20Guide.pdf">guide</a> to get Docker Desktop installed and running.
2. Follow the next <a href="">guide</a> to fork and install the "Learn Angular from Scratch" (lafs) repos. You will containerize both repos.
3. Follow the last <a href="https://github.com/adamsissoko/CS470/blob/main/documents/Guides/CS%20470%20Module%20Two%20Assignment%20-%20Docker%20Compose%20Guide.pdf">guide</a> to create a network of containers using Docker Compose.

4. Open a web browser and navigate to "http://localhost:3000" to access the API
5. Open another browser tab / window and navigate to "http://localhost:4200" to access the backend


<!-- USAGE EXAMPLES -->
## Usage

<h3>Front-end: User-Interactive Study Page</h3>
<p>You can explore the website <a href="http://adamsissokobucket.s3-website-us-east-1.amazonaws.com/">here</a>.</p>

<p>The front-end is designed to act as a study aid where users can dynamically engage with topics. Upon selecting a particular topic, the interface redirects to a dedicated question page for that topic. Here, users can exercise a range of functionalities:</p>

<ul>
  <li><strong>Add Questions:</strong> Users can contribute questions related to the selected topic.</li>
  <li><strong>Delete Questions:</strong> Any added question can be removed as well.</li>
  <li><strong>Interact with Questions:</strong> Upon selecting a specific question, users are given the option to add answers, facilitating a more interactive learning experience.</li>
</ul>

<p>This design aims to provide a versatile platform for users to focus on specific topics while having the flexibility to customize the study material.</p>

<table>
    <tr>
        <th>Question List</th>
        <th>Adding a Question</th>    
    </tr>
    <tr>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/questions.png" alt="[question list page]" style="height:300px;"></td>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/adding%20a%20question.png" alt="[adding a question]" style="height:300px;"></td>
    </tr>
        
</table>

<h3>Backend Architecture: AWS, Angular, Node.js, and DynamoDB</h3>
<p>The backend infrastructure leverages AWS services to deliver the front-end interface and manage data storage through DynamoDB. Lambda functions are employed for data access, interacting with the Amazon API Gateway. All front-end assets are securely hosted in an Amazon S3 bucket, as depicted in the accompanying image.</p>

<table>
    <tr>
        <th>S3 Bucket</th>
        <th>API Gateway</th>     
    </tr>
    <tr>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/S3Bucket.png" alt="[bucket]" style="height:auto;"></td>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/APIGateway.png" alt="[gateway]" style="height:auto;"></td>
   </tr>
</table>

<table>
    <tr>
        <th>DynamoDB Questions Table</th>
        <th>Lambda Function Sample</th>
   </tr>
    <tr>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/dynamoDBQuestions.png" alt="[dynamo]" style="height:auto;"></td>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/upsertLambdaFunction.png" alt="[lambda]" style="height:auto;"></td>
   </tr>
</table>

<h3>Local Testing Environment: Using Docker Compose</h3>
<p>Before transitioning the application to the AWS cloud, a rigorous testing phase was undertaken locally using Docker Compose. This was aimed at simulating the interplay between various components of the application.</p>

<p><strong>Setup Details:</strong></p>

<ul>
  <li><strong>Docker Desktop:</strong> Served as the primary dashboard for managing and observing container activities.</li>
  <li><strong>lafs-web:</strong> This container housed the front-end Angular application, making it accessible via a local host at port 4000.</li>
  <li><strong>lafs-api:</strong> The container responsible for the back-end, built on Node.js and Express.</li>
  <li><strong>MongoDB:</strong> Utilized as a local database, standing in for what would eventually be DynamoDB on AWS.</li>
</ul>

<p>This approach allowed for an isolated testing environment where each component could be scrutinized for functionality and interoperability. Once confident that the application was behaving as expected, the transition was made to deploy it on AWS.</p>

<table>
    <tr>
        <th>Docker Compose Project Running Locally</th>
    </tr>
    <tr>
        <td><img src="https://github.com/adamsissoko/CS470/blob/main/images/dockerComposeRunning.png" alt="[docker]" style="height:auto;"></td>
    </tr>
</table>

_For more information, please refer to the [Guides](https://github.com/adamsissoko/CS470/tree/main/documents/Guides)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Include guides
- [x] Compile screenshots
- [x] Link to documentation
- [x] Add final README

See the [open issues](https://github.com/adamsissoko/CS470/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Currently there is no license for this application, it is free to use by anyone who needs it. Please consider letting me know if it was helpful at all, or any additions you can propose (see the <a href="#contributing">contributing</a> section)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/adamsissoko/CS470.svg?style=for-the-badge
[contributors-url]: https://github.com/adamsissoko/CS470/graphs/contributors
  
[forks-shield]: https://img.shields.io/github/forks/adamsissoko/CS470.svg?style=for-the-badge
                
[forks-url]: https://github.com/adamsissoko/CS470/network/members
  
[stars-shield]: https://img.shields.io/github/stars/adamsissoko/CS470.svg?style=for-the-badge
[stars-url]: https://github.com/adamsissoko/CS470/stargazers
  
[issues-shield]: https://img.shields.io/github/issues/adamsissoko/CS470.svg?style=for-the-badge
[issues-url]: https://github.com/adamsissoko/CS470/issues
  
[license-shield]: https://img.shields.io/github/license/adamsissoko/CS470.svg?style=for-the-badge
[license-url]: https://github.com/adamsissoko/CS470/blob/master/LICENSE.txt
  
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=0077FF
[linkedin-url]: https://www.linkedin.com/in/adam-sissoko-3946a928a/

[product-screenshot]: images/main_page.png

[Node.js]: https://img.shields.io/badge/node.js-002200?style=for-the-badge&logo=nextdotjs&logoColor=green
[Node-url]: https://nodejs.org/en/
[Express.js]: https://img.shields.io/badge/Express-FFFFFF?style=for-the-badge&logo=express&logoColor=222222
[Express-url]: https://expressjs.com/
[Mongodb]: https://img.shields.io/badge/mongodb-003300?style=for-the-badge&logo=mongodb&logoColor=11FF11
[Mongodb-url]: https://www.mongodb.com/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[DynamoDB-url]: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html
[DynamoDB]: https://img.shields.io/badge/amazon_dynamodb-ccac00?style=for-the-badge&logo=amazondynamodb&logoColor=000000
[AWS]: https://img.shields.io/badge/amazon_aws-ccac00?style=for-the-badge&logo=amazonaws&logoColor=000000
[AWS-url]: https://aws.amazon.com/
[Docker]: https://img.shields.io/badge/docker-3232FF?style=for-the-badge&logo=docker&logoColor=ffffff
[Docker-url]: https://www.docker.com/
