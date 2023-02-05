<div id="top"></div>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<!-- PROJECT LOGO
<br />
  <a href="https://github.com/ReadRPO/readrpo.github.io">
    <img src="/touch-icon.png" alt="Logo" width="80" height="80">
  </a>
  --> 
<h3>ReadRPO Docs</h3>

  ReadRPO Docs is an open-source documentation website hosted on GitHub Pages. 
  It is distributed under the MIT license in `LICENSE`. 
  The software is fully open-source and available for anyone to view, fork, or edit.
  <br />
  <a href="https://github.com/ReadRPO/readrpo.github.io"><strong>Explore the docs »</strong></a>
  <br />
  <br />
  <a href="https://github.com/ReadRPO/readrpo.github.io">View Demo</a>
  ·
  <a href="https://github.com/ReadRPO/readrpo.github.io/issues">Report Bug</a>
  ·
  <a href="https://github.com/ReadRPO/readrpo.github.io/issues">Request Feature</a>
  </p>
</div>


<div align="left">

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
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


<!-- ABOUT THE PROJECT
## About The Project

[![ReadRPO][product-screenshot]](https://readrpo.github.io)
-->
<p align="right">(<a href="#top">Back to Top</a>)</p>



### Built With

* [Jekyll](https://jekyllrb.com/)
* [Jekyll Feed](https://github.com/jekyll/jekyll-feed)
* [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag)
* [Jekyll Sitemap](https://github.com/jekyll/jekyll-sitemap)
* [Jekyll Watch](https://github.com/jekyll/jekyll-watch)
* [Jekyll SASS Converter](https://github.com/jekyll/jekyll-sass-converter)
* [SASS](https://sass-lang.com/)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Use the following instructions to setup the project locally. 
Linux, Windows, or macOS are the preferred operating systems for these instructions.

### Prerequisites

The software required to install the respository are: 
A terminal, Ruby, and Jekyll. You may also optionally install the SASS compiler if CSS is preferred.

<br>

* Terminal install for Linux, Windows, or macOS:
~~~https
https://git-scm.com/downloads
~~~

<br>

* Ruby installation for Linux, Windows, or macOS:

Check for any existing Ruby versions
~~~sh
ruby -v
~~~
If there are none follow these instructions:
~~~https
https://www.ruby-lang.org/en/documentation/installation
~~~

<br>

* Jekyll installation for Linux, Windows, or macOS:
(Ruby, Gems, GCC, and MAKE are required)

Install Jekyll via Bundler Gems with Linux, Windows or macOS
~~~sh
gem install jekyll bundler
~~~

<br>

* SASS installation for Linux, Windows, or macOS:

Node.js installation for SASS on any operating system
~~~sh
npm install npm@latest -g
~~~

Chocolatey installation for SASS with Windows
~~~sh
choco install sass
~~~

Homebrew installation for SASS with Linux or macOS
~~~sh
brew install sass/sass/sass
~~~

#### Troubleshooting

* Visit [jekyllrb.com](https://jekyllrb.com/docs) for how to install Jekyll and its dependencies.
* Visit [ruby-lang.org](https://www.ruby-lang.org/en/documentation/installation) for how to install Ruby via command line.
* Visit [sass-lang.com](https://sass-lang.com/install) for how to install via differing applications.

<p align="right">(<a href="#top">Back to Top</a>)</p>
  
### Installation

1. Follow the Prerequisites
2. Clone the repo via SSH
   ~~~sh
   git clone git@github.com:ReadRPO/readrpo.github.io.git
   ~~~

   Clone the repo via HTTPS
   ~~~sh
   git clone https://github.com/ReadRPO/readrpo.github.io.git
   ~~~

3. Add your site and author details in `_config.yml`.

4. Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

5. ReadRPO Docs are already optimised for adding, updating and removing documentation pages in CloudCannon.
Add, update or remove a documentation page in the *Documentation* collection.

* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

6. Edit the Changelog

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

7. Edit the Search box

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

8. Edit the Navigation bar

* Change `site.show_full_navigation` to control all or only the current navigation group being open.

<p align="right">(<a href="#top">Back to Top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

ReadRPO is an intuitive tool to detect the location of a football player on a field using relative points and landmarks. 
This data can be rearranged into routes that would be drawn out based on their paths and trajectories. 
<br>

<br>

This provides the user with data that could be used to break down the tendencies of offense/defense, mark footage based off annotated data, and provide a dynamic for coaches to make executive decisions in real time.

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- ROADMAP -->
## Roadmap

* Project start date: (1/4/23)

### Detection component:
* ~90% accurate object detection (2/28/23)
* OBHS by (2/3/23)
* SBHS by (2/10/23)
* PHS by (2/17/23)
* MHS by (2/24/23)
* Finalization for object detection (2/28/23)

### Processing component:
* ~90% accurate class placement (3/31/23)


### Logic component:
* ...

<br>

<br>
See the [open issues](https://github.com/ReadRPO/readrpo.github.io/issues) for a full list of proposed features (and known issues).
  
<br>
  
<br>
  
<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">Back to Top</a>)</p>
  
<!-- CONTACT -->
## Contact

ReadRPO - Aarav Batra
<br>
Email us at aaravbatra@duck.com

Project Link: [https://github.com/ReadRPO/readrpo.github.io](https://github.com/ReadRPO/readrpo.github.io)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Othneil Drew for the Best README Template](https://github.com/othneildrew/Best-README-Template)
* [CloudCannon for the Edition Jekyll Template](https://github.com/CloudCannon/edition-jekyll-template)
* [Shields.io for the README.md headers](https://shields.io)
* [Aarav Batra for curating this project with ❤️](https://github.com/ReadRPO)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/ReadRPO/readrpo.github.io.svg?style=for-the-badge
[contributors-url]: https://github.com/ReadRPO/readrpo.github.io/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ReadRPO/readrpo.github.io.svg?style=for-the-badge
[forks-url]: https://github.com/ReadRPO/readrpo.github.io/network/members
[stars-shield]: https://img.shields.io/github/stars/ReadRPO/readrpo.github.io.svg?style=for-the-badge
[stars-url]: https://github.com/ReadRPO/readrpo.github.io/stargazers
[issues-shield]: https://img.shields.io/github/issues/ReadRPO/readrpo.github.io.svg?style=for-the-badge
[issues-url]: https://github.com/ReadRPO/readrpo.github.io/issues
[product-screenshot]: images/_screenshot.png
