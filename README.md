<!-- This README.md layout style was inspired by 'othneildrew' found here: https://github.com/othneildrew/Best-README-Template -->

<!-- This gives the ability to provide 'back to the top links -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out this User Login Project. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement", "feature", "bug", "question" and more.
*** Don't forget to give this User Login System Project a star!
*** Thanks again! Now go create something AMAZING too! :D
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
[![License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ProfCyberNaught/php-login-system/">
    <img src="images/procn-user-login-system-logo.png" alt="User Login System Logo" width="80" height="80">
  </a>

  <h3 align="center">User Login System Project - Prof Cyber Naught</h3>

  <p align="center">
    A user login system providing encrypted data storage!
    <br />
    <a href="https://github.com/ProfCyberNaught/php-login-system/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ProfCyberNaught/php-login-system/">View Demo</a>
    ·
    <a href="https://github.com/ProfCyberNaught/php-login-system/issues">Report Bug</a>
    ·
    <a href="https://github.com/ProfCyberNaught/php-login-system/issues">Request Feature</a>
  </p>
</div>



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



<!-- ABOUT THE PROJECT -->
## About The Project

[![User Login System Screen Shot][product-screenshot]](https://github.com/ProfCyberNaught/php-login-system/)

There are many tutorials online attempting to teach people how to code a user Login System. However, many of them are either out-of-date in terms of language, or no longer follow best security practices (or never did in the first place). This project is dedicated to creating a user login system that not only would be up to date regarding languages, but also include best security practices involving but not limited to: password hashing, cross-site scripting protections (XSS), SQL Injection protections, data storage (encryption by default).

Here's why:
* Your time should be focused on coding with the latest language version :muscle:
* You shouldn't be learning to develop systems without using best security practices :thumbsdown:
* You should be implementing encryption-as-standard methodology (providing better storage security and privacy if the database is compromised) :thumbsup:

Of course, no one user login system will serve all projects since your needs may be different. So I'll be adding more features in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people who have contributed to expanding this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![PHP][PHP]][PHP-url]
* [![SQL][SQL]][SQL-url]
* [![HTML][HTML]][HTML-url]
* [![CSS][CSS]][CSS-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

If you want to have this User Login System running locally, you can follow the instructions below to get a local copy up and running.

### Prerequisites

This is a list of the things you will need to use the User Login System.

* Apache
* PHP 8
* MySQL or MariaDB
* PHPMyAdmin
* Sodium Library
* Repo Main.zip
* Text Editor
* Web Browser

### Installation

_If you want to have this project running on your local environment, follow these instructions._

1. Download the repo from: https://github.com/ProfCyberNaught/php-login-system/archive/refs/heads/main.zip
2. Download & install XAMPP or LAMP (depending on your operating system and personal choice)
3. Make sure you have libsodium packages enabled (libsodium.dll) (may need to download or copy across to different directories to work)
4. Extract the compressed zip file to the drive location of your localhost (sometimes 'www' or 'htdocs')
5. Create a database with a username and password (use PHPMyAdmin for this)
6. Import the database file (pcn_database.sql) using PHPMyAdmin (stored in /pcn_config/pcn_database/ directory)
7. Add your new database credentials to the pcn_db_config.php file (stored in /pcn_config/ directory)
8. Direct your browser to /localhost/your-directory (replace with your chosen directory name)
9. Login with the default credentials (u: procn  p: procnpw)
10. Change the default login credentials

If you are using XAMPP, use the following link to enable the Sodium Library: [Sodium Library - XAMPP](https://stackoverflow.com/questions/48287186/sodium-is-not-loading-on-xampp-php-7-2)<br />
However, if you are using another environment, please check the online forums or software installation guides for your chosen application.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

I will use this space to show useful examples of how the project can be used. Additional screenshots, code examples and demos may work well in this space. Could also link to more resources.

_For more examples, please refer to the [Documentation](https://github.com/ProfCyberNaught/php-login-system/)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

This roadmap should only reflect the larger concepts and features (initially it might reflect the smaller tasks).

- [ ] Add Changelog
- [x] Add back to top links
- [x] Add "readme" document to introduce the project
- [ ] Add "readme" content
    - [x] Roadmap
    - [ ] Installation Instructions
    - [ ] Prerequisites
    - [ ] Update Screenshot Image (when available)
    - [ ] Update Logo Image (when available)
    - [ ] Fix License Issue (Not Specified)
    - [ ] Contributing Instructions
    - [x] Add Mastodon Link
    - [x] Add Website Link
    - [x] Add Encrypted Email Link (+ public key)

See the [open issues](https://github.com/ProfCyberNaught/php-login-system/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
You can also join the discussions board. Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**Security Advisories:** This repo supports private security advisories to either discuss, fix, or publish information about security vulnerabilities.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-3.0 License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Mastodon: [@profcybernaught](https://infosec.exchange/@ProfCyberNaught)

Encrypted Email: [profcybernaught - Proton - me](#)

Public Email Key: [Public Encryption Key](https://github.com/ProfCyberNaught/php-login-system/blob/main/Public%20Encryption%20Key%20-%20Email/publickey.profcybernaught%40proton.me-17967b5f67efc9e9c294ef224e47d1ba21f7a275.asc)

Project Link: [https://github.com/users/ProfCyberNaught/projects/1](https://github.com/users/ProfCyberNaught/projects/1)

Website Link: [https://profcybernaught.hashnode.dev/](https://profcybernaught.hashnode.dev/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

A list of resources that may interest you:

* [Choose an Open Source License](https://choosealicense.com)
* [Caiyongji Emoji List](https://github.com/caiyongji/emoji-list)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [Ant Design Icons](https://github.com/ant-design/ant-design-icons)
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
* [Simple Icons](https://simpleicons.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ProfCyberNaught/php-login-system.svg?style=for-the-badge
[contributors-url]: https://github.com/ProfCyberNaught/php-login-system/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ProfCyberNaught/php-login-system.svg?style=for-the-badge
[forks-url]: https://github.com/ProfCyberNaught/php-login-system/network/members
[stars-shield]: https://img.shields.io/github/stars/ProfCyberNaught/php-login-system.svg?style=for-the-badge
[stars-url]: https://github.com/ProfCyberNaught/php-login-system/stargazers
[issues-shield]: https://img.shields.io/github/issues/ProfCyberNaught/php-login-system.svg?style=for-the-badge
[issues-url]: https://github.com/ProfCyberNaught/php-login-system/issues
[license-shield]: https://img.shields.io/github/license/ProfCyberNaught/php-login-system.svg?style=for-the-badge
[license-url]: https://github.com/ProfCyberNaught/php-login-system/blob/main/LICENSE
[product-screenshot]: images/procn-user-login-system-screenshot.png
[PHP]: https://img.shields.io/badge/PHP-000000?style=for-the-badge&logo=PHP&logoColor=purple
[PHP-url]: https://www.php.net/
[HTML]: https://img.shields.io/badge/html-000000?style=for-the-badge&logo=HTML5&logoColor=E34F26
[HTML-url]: https://www.w3schools.com/html/
[CSS]: https://img.shields.io/badge/CSS-000000?style=for-the-badge&logo=CSS3&logoColor=1572B6
[CSS-url]: https://www.w3schools.com/Css/
[SQL]: https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=MySQL&logoColor=4479A1
[SQL-url]: https://www.w3schools.com/sql/

