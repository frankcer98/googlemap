
<!-- PROJECT SHIELDS -->
[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- TABLE OF CONTENTS -->
## Table of Contents
* [About the Project](#about-the-project)
* [Prerequisites](#prerequisites)
  * [Libraries](#libraries)
  * [Google Map API](#google-map-api)
  * [Installation](#installation)
* [Usage](#Usage)
* [Contributing](#contributing)
* [Maintainer](#maintainer)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About the Porject

The project can do a brand or a category nearby search for specific locations, and get the Geodata into an excel document as tabular format. For example, you want to know how many fast-food restaurants (includes addresses) within 5 miles of Ivy League schools.

<!-- PREREQUISITES -->
## Prerequisites
### Libraries
This was created and tested using Python3.7 and using some libraries including [openpyxl](https://openpyxl.readthedocs.io/), [googlemaps](https://github.com/googlemaps/google-maps-services-python), [prettyprinter](https://github.com/tommikaikkonen/prettyprinter), [urllib3](https://urllib3.readthedocs.io). These libraries are needed. To install with pip:

```bash
pip install openpyxl
pip install googlemaps
pip install urllib3
pip install prettyprinter
```
#### Google Map API
The project also requires [Google Map API Key](https://developers.google.com/maps). Please register and fill your API Key into the program.

```bash
api_key = 'Enter your Google Map API HERE'

if api_key is False:
    print("API is False")
else:
    serviceurl = 'https://maps.googleapis.com/maps/api/geocode/json?'
```

#### Installation
Clone the repository
```sh
git clone https://github.com/nathanliu100/googlemap.git
```

<!-- USAGE -->
## Usage

Will add the usage when I have time. Thanks~




<!-- CONTRIBUTING & MANINTAINER -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Maintainer
[@nathanliu100](https://github.com/nathanliu100/)

## License
[MIT © Yongliang Liu](https://github.com/nathanliu100/googlemap/blob/master/LICENSE)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[stars-shield]: https://img.shields.io/github/stars/nathanliu100/googlemap?style=flat-square
[stars-url]: https://github.com/nathanliu100/googlemap/stargazers
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/nathanliu100/googlemap/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/yongliangliu/
