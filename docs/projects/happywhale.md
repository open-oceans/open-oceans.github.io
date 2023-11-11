# Simple CLI for Happywhale

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=plastic&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samapriya/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@samapriyaroy)
[![Twitter URL](https://img.shields.io/twitter/follow/samapriyaroy?style=social)](https://twitter.com/intent/follow?screen_name=samapriyaroy)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/109627075086849826?domain=https%3A%2F%2Fmapstodon.space%2F)](https://mapstodon.space/@samapriya)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10081817.svg)](https://doi.org/10.5281/zenodo.10081817)
[![CI happywhale](https://github.com/open-oceans/happywhale/actions/workflows/package_ci.yml/badge.svg)](https://github.com/open-oceans/happywhale/actions/workflows/package_ci.yml)
[![Hits-of-Code](https://hitsofcode.com/github/open-oceans/happywhale?branch=main)](https://hitsofcode.com/github/open-oceans/happywhale?branch=main)
[![PyPI version](https://badge.fury.io/py/happywhale.svg)](https://badge.fury.io/py/happywhale)
[![Donate](https://img.shields.io/badge/Donate-Buy%20me%20a%20Coffee-teal)](https://www.buymeacoffee.com/samapriya)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/samapriya)
[![Donate](https://img.shields.io/badge/Donate-Buy%20me%20a%20Chai-teal)](https://www.buymeacoffee.com/samapriya)

[Happywhale is a global citizen science project](https://happywhale.com) dedicated to whale and dolphin research and conservation. The user-friendly Happywhale app allows anyone to share photos of encounters with these marine mammals, which are then processed by a team of scientists and volunteers using advanced image recognition algorithms. Identified individuals are tracked over time and across locations, yielding valuable insights into their behavior and aiding  in the preservation of critical habitats.

The CLI is designed to interact with the website and allow for you to perform operations like search, download and more using underlying api end points. The CLI provides tools based on API endpoints that may change and evolve and can lead to compatibility issues without API documentations so this tool will be developed as needed to support the larger community needs.

**Disclaimer: This is an unofficial tool. Is not licensed or endorsed by Happywhale.com. It is created and maintained by Samapriya Roy.**

```
happywhale -h
usage: happywhale.py [-h] {readme,auth,species,stats,fetch,search,download} ...

Simple CLI for HappyWhale API

positional arguments:
  {readme,auth,species,stats,fetch,search,download}
    readme              Go to the web based happywhale cli readme page
    auth                Saves your username and password
    species             Get species list
    stats               Go site stats for happywhale
    fetch               Fetch details on an encounter based on encounter id
    search              Search and export results (Default: Global 1 month)
    download            Download images from search results (Default: Global 1 month)

options:
  -h, --help            show this help message and exit
```

#### Citation

You can cite the tool too

```
Samapriya Roy. (2023). open-oceans/happywhale: Simple CLI for Happywhales.com API (0.0.2).
Zenodo. https://doi.org/10.5281/zenodo.10081817
```
