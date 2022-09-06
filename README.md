<h1 align="center">Image Uploader</h1>

<div align="center">
   Solution for a challenge from  <a href="http://devchallenges.io" target="_blank">Devchallenges.io</a>.
</div>
<div align="center">
  <h3>
    <a href="https://image-uploader-app.onrender.com">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/Yadira-Ferrer/Image-Uploader-App">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenges/O2iGT9yBd6xZBrOcVirx">
      Challenge
    </a>
  </h3>
</div>

## Table of Contents

- [Overview](#overview)
  - [Built With](#built-with)
- [Features](#features)
- [How to use](#how-to-use)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Overview

![screenshot](https://devchallengesyf.s3.us-east-2.amazonaws.com/resources/image-uploader.gif)

![darktheme](https://devchallengesyf.s3.us-east-2.amazonaws.com/resources/image-uploader-theme.gif)

The project was deployed on [Render](https://render.com/) you can see here the [Demo](https://image-uploader-app.onrender.com/). 

### Built With

- [Angular v12](https://angular.io/)
- [PrimeNG v13](https://www.primefaces.org/primeng-v13/)
- [Prime Icons](https://www.primefaces.org/primeng-v13/icons)
- [Node.js](https://nodejs.org/es/)
- [Express](https://expressjs.com/es/)
- [AWS S3](https://aws.amazon.com/es/s3/?trk=5970b1e9-218b-48cc-9862-f23c151d81b2&sc_channel=ps&s_kwcid=AL!4422!3!590443989054!e!!g!!aws%20s3&ef_id=Cj0KCQjw39uYBhCLARIsAD_SzMTRny15HuKxFRhIoSHmynpC3znAK5TAzl0E2VTUTAFdaMR7mlwAqxkaAnOvEALw_wcB:G:s&s_kwcid=AL!4422!3!590443989054!e!!g!!aws%20s3)

## Features

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges) challenge. The [challenge](https://devchallenges.io/challenges/O2iGT9yBd6xZBrOcVirx) was to build an application to complete the following user stories:

- **User story:** I can drag and drop an image to upload it
- **User story:** I can choose to select an image from my folder
- **User story:** I can see a loader when uploading
- **User story:** When the image is uploaded, I can see the image and copy it
- **User story:** I can choose to copy to the clipboard

Additionally, it's available an option to change the theme to dark theme.

> :exclamation: :exclamation: **Note**: *The images are stored in an AWS S3 bucket, but it will be removed after some time because the bucket has a lifecycle rule configured that keep the files for just one day.* 

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/your-user-name/your-project-name

# Install dependencies
$ npm install

# Run the app
$ npm start
```

## Acknowledgements

- [PrimeNG Dynamic Theming at Runtime](https://www.youtube.com/watch?v=5VOuUdDXRsE)

## Contact

- GitHub [@Yadira-Ferrer](https://github.com/Yadira-Ferrer)
