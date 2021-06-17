# `Team Elle` Submission or project name 

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/get-started/) [![Website](https://img.shields.io/badge/View-Website-blue)](https://sample-project.s3-web.us-east.cloud-object-storage.appdomain.cloud/)

A brief overview of our idea for the [Call for Code](https://developer.ibm.com/callforcode/) initiative. 



## :fallen_leaf: Contents :


  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Live demo](#live-demo)
  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

In rural and semi-rural communities, there is a lack of understanding of various diseases and health complications due to water contamination and improper sanitation. As a result, millions of children lose their lives each year across the planet, teenagers and adults get diseases that they carry for the rest of their lives, and environmental damage. Due to improper exclusion and timely quarantines, from a few people, entire communities may be affected. It may be from air & plasma borne diseases like COVID19, Influenza, Tuberculosis, and water-borne diseases like Arsenic Pollution, Typhoid, Dysentry and Hepatitis.

### How can technology help?

With modern technology, combining IoT, Advanced Algorithms, Machine Learning and Smart-Interaction methods with Artificial Intelligence, the diseases can be prevented by imposing smart sanitation systems to improve hygiene and community-symptoms monitoring systems. Smart Sanitation can also have an added advantage, methods to save and control unnecessary water wastage, thus improving the ecological balance.

### The idea

The idea is to set up smart-community hubs across multiple physical locations with an interactive system to govern the area. It will do the following :
1) Monitor the water sources with smart sensory data
2) Maintain water analysis reports and trigger a response if threshold is crossed
3) Keep an average population count of the blocks of communities assigned per community hub
4) Keep solo count of disease symptoms reported regularly at every block and raise alarm if threshold goes above a pre-determined level. 
`Explanation --Say a person from Block A reported of Nausea, Vomiting and Severe Diarrhea on Jan 01. On the next couple of days, similar reports started to get logged in the system. The system will immediately validate the sensory data, water quality at sources, and trigger a response to the controller for immediate remedial action. `

## Demo video

[![Watch the video](https://github.com/Call-for-Code/Liquid-Prep/blob/master/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

## The architecture

![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.


## Project roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/roadmap.jpg)

## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [sample-react-app](./sample-react-app/)
- [sample-angular-app](./sample-angular-app/)
- [Explore other projects](https://github.com/upkarlidder/ibmhacks)

## Live demo

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/).

## Built with

- [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
- [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency management
- [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
