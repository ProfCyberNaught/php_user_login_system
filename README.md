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
[![Contributions][contributions]][contributions-url]
[![Discussions][discussions]][discussions-url]
[![Contributor Covenant][Contributor-Covenant]][Contributor-Covenant-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ProfCyberNaught/php_user_login_system/">
    <img src="pcn_images/pcn_user_login_system_logo.png" alt="User Login System Logo - ProfCyberNaught" width="80" height="80">
  </a>

  <h3 align="center">PHP User Login System Project - @ProfCyberNaught</h3>

  <p align="center">
    A PHP user login system providing encrypted data storage!
    <br />
    <a href="https://github.com/ProfCyberNaught/php_user_login_system/blob/main/pcn_docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ProfCyberNaught/php_user_login_system/">View Demo</a>
    ·
    <a href="https://github.com/ProfCyberNaught/php_user_login_system/issues">Report Bug</a>
    ·
    <a href="https://github.com/ProfCyberNaught/php_user_login_system/issues">Request Feature</a>
    ·
    <a href="https://github.com/ProfCyberNaught/php_user_login_system/discussions">Discussions</a>
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
## About The PHP User Login System Project

[![User Login System Screen Shot][product-screenshot]](https://github.com/ProfCyberNaught/php_user_login_system/)

There are many tutorials online attempting to teach people how to code a PHP User Login System. However, many of them are either out-of-date in terms of language, or no longer follow best security practices (or never did in the first place). This project is dedicated to creating a PHP User Login System that not only would be up to date regarding languages, but also include best security practices involving but not limited to: password hashing, cross-site scripting protections (XSS), SQL Injection protections, data storage (encryption by default).

Here's why:
* Your time should be focused on coding with the latest language version :muscle:
* You shouldn't be learning to develop systems without using best security practices (these change over time) :thumbsdown:
* You should be implementing encryption-as-standard methodology (providing better storage security and privacy if the database is compromised) :thumbsup:

Of course, no _one_ PHP User Login System will serve all projects since your needs may be different. So I'll be adding more features as the project develops. You may also suggest changes by creating an issue (if one does not already exist), forking this repo and creating a pull request. Thanks to all the people who have contributed to expanding this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![PHP][PHP]][PHP-url]
* [![SQL][SQL]][SQL-url]
* [![HTML][HTML]][HTML-url]
* [![CSS][CSS]][CSS-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

If you want to have this PHP User Login System running locally, you can follow the instructions below to get a local copy up and running.

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

_If you want to have this PHP User Login System project running on your local environment, follow these instructions._

1. Download the repo from: https://github.com/ProfCyberNaught/php_user_login_system/archive/refs/heads/main.zip
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

_For more examples, please refer to the [Documentation](https://github.com/ProfCyberNaught/php_user_login_system/blob/main/pcn_docs)_

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

See the [open issues](https://github.com/ProfCyberNaught/php_user_login_system/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
You can also join the discussions board. Don't forget to give the project a star! Thanks again!

1. Create an Issue (if one does not already cover your contribution)
2. Discuss your issue with the project maintainer (use discussion board if required)
3. Fork the Project (based on maintainer feedback)
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request (supply a description of your changes)

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

Public Email Key: [Public Encryption Key](https://github.com/ProfCyberNaught/php_user_login_system/blob/main/pcn_pek_email/)

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
[contributors-shield]: https://img.shields.io/github/contributors/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[contributors-url]: https://github.com/ProfCyberNaught/php_user_login_system/graphs/contributors
[contributions]: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge
[contributions-url]: https://github.com/ProfCyberNaught/php_user_login_system/
[discussions]: https://img.shields.io/github/discussions/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[discussions-url]: https://github.com/ProfCyberNaught/php_user_login_system/discussions
[forks-shield]: https://img.shields.io/github/forks/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[forks-url]: https://github.com/ProfCyberNaught/php_user_login_system/network/members
[stars-shield]: https://img.shields.io/github/stars/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[stars-url]: https://github.com/ProfCyberNaught/php_user_login_system/stargazers
[issues-shield]: https://img.shields.io/github/issues/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[issues-url]: https://github.com/ProfCyberNaught/php_user_login_system/issues
[license-shield]: https://img.shields.io/github/license/ProfCyberNaught/php_user_login_system.svg?style=for-the-badge
[license-url]: https://github.com/ProfCyberNaught/php_user_login_system/blob/main/LICENSE
[product-screenshot]: pcn_images/pcn_user_login_system_screenshot.png
[PHP]: https://img.shields.io/badge/PHP-000000?style=for-the-badge&logo=PHP&logoColor=purple
[PHP-url]: https://www.php.net/
[HTML]: https://img.shields.io/badge/html-000000?style=for-the-badge&logo=HTML5&logoColor=E34F26
[HTML-url]: https://www.w3schools.com/html/
[CSS]: https://img.shields.io/badge/CSS-000000?style=for-the-badge&logo=CSS3&logoColor=1572B6
[CSS-url]: https://www.w3schools.com/Css/
[SQL]: https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=MySQL&logoColor=4479A1
[SQL-url]: https://www.w3schools.com/sql/
[Contributor-Covenant]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=for-the-badge
[Contributor-Covenant-url]: code_of_conduct.md