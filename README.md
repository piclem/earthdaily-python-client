<div id="top"></div>
<!-- PROJECT SHIELDS -->
<!--
*** See the bottom of this document for the declaration of the reference variables
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/GEOSYS">
    <img src="https://earthdailyagro.com/wp-content/uploads/2022/01/Logo.svg" alt="Logo" width="400" height="200">
  </a>

  <h1 align="center">EarthDaily Python Client</h3>

  <p align="center">
    Your gateway to the Earth Data Store STAC Catalog.
    <br />
    <a href="https://earthdailyagro.com/"><strong>Who we are</strong></a>
    <br />
    <br />
    <a href="https://github.com/GEOSYS/earthdaily">Project description</a>
    ·
    <a href="https://github.com/GEOSYS/earthdaily-python-client/issues">Report Bug</a>
    ·
    <a href="https://github.com/GEOSYS/earthdaily-python-client/issues">Request Feature</a>
  </p>
</p>


<div align="center">

[![PyPI version](https://badge.fury.io/py/earthdaily.png)](https://badge.fury.io/py/earthdaily)
[![Documentation](https://img.shields.io/badge/Documentation-html-green.svg)](https://geosys.github.io/earthdaily-python-client/)
[![pytest-main](https://github.com/GEOSYS/earthdaily-python-client/actions/workflows/pytest-prod.yaml/badge.svg)](https://github.com/GEOSYS/earthdaily-python-client/actions/workflows/pytest-prod.yaml)

[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]
[![Youtube][youtube-shield]][youtube-url]
[![languages][language-python-shiedl]][issues-url]
<!-- [![CITest][CITest-shield]][CITest-url]-->
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
  
</div>


<!--[![Stargazers][GitStars-shield]][GitStars-url]-->
<!--[![Forks][forks-shield]][forks-url]-->
<!--[![Stargazers][stars-shield]][stars-url]-->


<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#support-development">Support development</a></li>
    <li><a href="#resources">Resources</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#copyrights">Copyrights</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

In the realm of geospatial data analysis and Earth observation, the EarthDaily Python package emerges as a powerful toolset that seamlessly connects you to the vast and invaluable Stac catalog Earth Data Store. This package is designed with the vision of simplifying and optimizing your workflow, ensuring that you can harness the full potential of Earth observation data with ease and efficiency.

Our package is built upon a foundation of best practices, meticulously crafted to elevate your data analysis experience. With EarthDaily, you can effortlessly navigate the complexities of datacube creation, including crucial processes like conversion to reflectance and automatic clipping to your area of interest. Additionally, we've taken care to make EarthDaily fully compatible with Dask, enabling you to scale your data preprocessing tasks with confidence and precision.


## Features

See [documentation](https://geosys.github.io/earthdaily-python-client/) for more information

## Getting started

### Prerequisites

Make sure you have valid EDS credentials. If you need to get trial access, please contact us.

This package has been tested on Python 3.10.11.


### Installing

#### Using pip 

`pip install earthdaily`

#### Planned : Using conda/mamba

### Authentication
Authentication credentials are accessed from environment variables. As a convenience python-dotenv is supported. 
Copy the `.env.sample` file and rename to simply `.env` and update with your credentials. This file is gitignored. 
Then add to your script/notebook:

```python3
from dotenv import load_dotenv

load_dotenv()  # take environment variables from .env.
```

### Usage

See the documentation for more information.

### Support development

If you find this package useful, please consider supporting its development.


<!-- RESOURCES -->
## Resources 
The following links will provide access to more information:
- [EarthDaily agro developer portal  ](https://developer.geosys.com/)
- [Pypi package](https://pypi.org/project/geosyspy/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Support development

If this project has been useful, that it helped you or your business to save precious time, don't hesitate to give it a star.

<p align="right">(<a href="#top">back to top</a>)</p>

## License

Distributed under the [GPL 3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html). 

<p align="right">(<a href="#top">back to top</a>)</p>

## Contact

For any additonal information, please [email us](mailto:sales@earthdailyagro.com).

<p align="right">(<a href="#top">back to top</a>)</p>

## Copyrights

© 2022 Geosys Holdings ULC, an Antarctica Capital portfolio company | All Rights Reserved.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- List of available shields https://shields.io/category/license -->
<!-- List of available shields https://simpleicons.org/ -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=social
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=plastic&logo=appveyor
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/qgis-plugin/repo.svg?style=plastic&logo=appveyor
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/GEOSYS/GeosysPy/repo.svg?style=social
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/GEOSYS/qgis-plugin
[license-url]: https://www.gnu.org/licenses/gpl-3.0.en.html
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=social&logo=linkedin
[linkedin-url]: https://www.linkedin.com/company/earthdailyagro/mycompany/
[twitter-shield]: https://img.shields.io/twitter/follow/EarthDailyAgro?style=social
[twitter-url]: https://img.shields.io/twitter/follow/EarthDailyAgro?style=social
[youtube-shield]: https://img.shields.io/youtube/channel/views/UCy4X-hM2xRK3oyC_xYKSG_g?style=social
[youtube-url]: https://img.shields.io/youtube/channel/views/UCy4X-hM2xRK3oyC_xYKSG_g?style=social
[language-python-shiedl]: https://img.shields.io/badge/python-3.9-green?logo=python
[language-python-url]: https://pypi.org/ 
[GitStars-shield]: https://img.shields.io/github/stars/GEOSYS?style=social
[GitStars-url]: https://img.shields.io/github/stars/GEOSYS?style=social
[CITest-shield]: https://img.shields.io/github/workflow/status/GEOSYS/GeosysPy/Continous%20Integration
[CITest-url]: https://img.shields.io/github/workflow/status/GEOSYS/GeosysPy/Continous%20Integration