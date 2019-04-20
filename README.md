<!-- PROJECT SHIELDS -->
[![Build Status][build-shield]]()
[![Contributors][contributors-shield]]()
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/a01334390/EvacuationSimulator">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Evacuation Simulator</h3>

  <p align="center">
    Tecnologico de Monterrey's Evacuation Simulator using GLUT, MagicaVoxel, and Bezier curves
    <br />
    <a href="https://github.com/a01334390/EvacuationSimulator"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/a01334390/EvacuationSimulator">View Demo</a>
    ·
    <a href="https://github.com/a01334390/EvacuationSimulator/issues">Report Bug</a>
    ·
    <a href="https://github.com/a01334390/EvacuationSimulator/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/a01334390/EvacuationSimulator)

This application is meant to simulate the way people would move through the evacuation of the university's new building, Legorreta (Edificio Sur). This simulation is meant to create a better and more advanced understanding the possible routes people could take, their overall cost, and how could they be further optimized to reduce the evacuation times.

These models were created using data produced by Mavic 2 Pro drones and textures provided by the Photo club.

### Built With
This application was built using the following frameworks:

* [GLUT](https://www.opengl.org/resources/libraries/glut/)
* [MagicaVoxel](https://ephtracy.github.io)
* [Adobe Illustrator](https://www.adobe.com/products/illustrator.html)


<!-- GETTING STARTED -->
## Getting Started

This is a small guide to get you started.

### Prerequisites

You need to install GLUT (or FreeGlut as GLUT is no longer being supported)
```sh
sudo apt-get install freeglut3-dev
```

To confirm all the required packages have been installed, you'll need to execute:

```sh
dpkg -L freeglut3-dev
```

```sh
/usr/include/GL
/usr/include/GL/freeglut.h
/usr/include/GL/freeglut_ext.h
/usr/include/GL/freeglut_std.h
/usr/include/GL/glut.h
/usr/lib/x86_64-linux-gnu/libglut.a
...
/usr/lib/x86_64-linux-gnu/libglut.so
```

### Installation

1. In the same folder where the Makefile resides, execute the following command:
```sh
make
```
2. Then, to execute the application, execute the following:
```sh
./Debug/main
```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Fernando Martin Garcia Del Angel - [martntn](https://www.linkedin.com/in/martntn/) - martingarciadelangel@me.com
Project Link: [https://github.com/a01334390/EvacuationSimulator](https://github.com/a01334390/EvacuationSimulator)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)


<!-- MARKDOWN LINKS & IMAGES -->
[build-shield]: https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat-square
[contributors-shield]: https://img.shields.io/badge/contributors-1-orange.svg?style=flat-square
[license-shield]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square
[license-url]: https://choosealicense.com/licenses/mit
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/screenshot.png
