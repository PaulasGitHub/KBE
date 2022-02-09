# KBE Project "Christmasshop"

<img src="https://c.tenor.com/9gapUwomsxsAAAAd/kitten-christmas.gif" alt="A kitten walks towards the camera. On its tail are drawn christmas decorations so that it looks like a christmas tree." height="200px">

## Project assignment for "Komponentenbasierte Entwicklung"
_Hochschule für Technik und Wirtschaft Berlin, WiSe21/22_

---

## Table of contents
* [Description](#description)
* [Installation & Run](#installation-and-run)
* [Architecture & Implementation](#architecture-and-implementation)
* [Used Technologies](#used-technologies)
* [Contributors](#contributors)
* [License](#license)

## Description
Welcome to our component-based-development project "Christmasshop" in the Wintersemester 21/22. 
Our goal was to implement a project consisting of various services representing an online shop for delightful Christmas decorations.<br>

The full project includes:
* Application Microservice
* Calculator Service
* Storage Service
* Gateway Service
* Frontend

Which can all be found as submodules to this repo.

## Installation and Run
To start the whole Project [Rebex SFTP server](https://www.rebex.net/tiny-sftp-server/) is required. Clone all required submodules, install the required components and run each service. <br>

Apart from the frontend, all services in this project require [Maven](https://maven.apache.org/install.html) to run. <br>
After cloning the repos and once Maven is installed, enter 

```sh
./mvnw spring-boot:run
```
in your terminal.<br>

The frontend requires [Node.js](https://nodejs.org/) to run. <br>

```sh
cd <projektfolder>
npm install
```
To start the server
```sh
npm start
```
And open the app in your favourite browser (we recommend [Firefox](https://www.mozilla.org/en-US/firefox/download/thanks/)) via ```localhost:3000 ```.

## Architecture and Implementation

<br>

<img src="http://drive.google.com/uc?export=view&id=1ZSA4qckagWg2Giyt0KnQkws5NUgj8vA8" alt="Component diagram of the Christmasshop" height="300px"> <br>
(_image: Architecture diagram_)

<img src="http://drive.google.com/uc?export=view&id=1lb1zSSAon0Rccgquj1Yp9BHuq1tbndeg" alt="Sequence diagram of the Christmasshop" width="300px"> <br>
(_image: Sequence diagram_)

## Used Technologies
* [Docker](https://www.docker.com/products/docker-desktop)
* [JUnit](https://junit.org/junit5/)
* [Lombok](https://projectlombok.org/)
* [Maven](https://maven.apache.org/)
* [Mockito](https://site.mockito.org/)
* [Node.js](https://nodejs.org/)
* [PostgreSQL](https://projectlombok.org/)
* [React](https://reactjs.org/)
* [Redis](https://redis.io/)
* [SLF4J](slf4j)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Swagger](https://swagger.io/)

## Contributors
|  Name  | MatrikelNr. | GithubRepo| 
| ------ | ------ | ------ |
| Ekaterina Krysenkova | 0573734 |[link](https://github.com/Krysenkova)
| Paula Katharina Pätzold | 0573372 | [link](https://github.com/PaulasGitHub)

## License
Copyright 2022 Krysenkova, Pätzold

Licensed under the [Apache License, Version 2.0](LICENSE) (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


<img src="https://c.tenor.com/SYpRfoThETsAAAAC/black-cat-christmas-tree.gif" alt="A lot of black cats are photoshopped together to resemble the shape of a christmas tree. Their eyes are blinking irregularly, mimicking fairy lights." height="500px">


