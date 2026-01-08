<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<h1 align="center">Search Engine</h3>
  <p align="center">
    A scalable search engine which can be utilized to find websites on the Internet
  </p>
  <p align="center">
    <strong>EECS 485</strong> <br> November - December 2024
  </p>
</div>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0dcd3e38-4263-4932-abde-aacc66399186" alt="animated" />
</p>


## Table of Contents

   * [About The Project](#about-the-project)
   * [Tools and Languages](#tools-and-languages)
   * [Features](#features)
   * [Components](#components)
   * [Acknowledgments](#acknowledgments)


<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center">
  A working search engine that allows for information retrieval utilizing a Service-Oriented Architecture to scale dynamic pages and web search. As a whole, this project aims to imitate the same kinds of experiences found in popular search engines such as Google and Bing, with a variety of hyperlinks displayed to user based on the relative importance of each website.
</p>

## Tools and Languages
<!-- [![C++][cplusplus]][cplusplus-url] -->

[![Python][python]][python_url]
[![HTML][html]][html_url]
[![CSS][css]][css_url]
[![SQLite][sqlite]][sqlite_url]

[![Flask][flask]][flask_url]
[![Jinja][jinja]][jinja_url]
[![PyCharm][pycharm]][pycharm_url]


<!-- FEATURES -->
## Features

- [ ] Created a Flask application in a Python virtual environment in order to connect to database and rendered webpages
- [ ] Utilized SQLite to create and store information about each website (ie. document ID, score, title, url, and summary)
- [ ] Text analysis (tf-idf) and link analysis (PageRank) + parallel data processing with MapReduce
- [ ] Rendered website pages by using templates and their context using the Jinja2 library

## Components

- Created a segmented inverted index of web pages using a pipeline of MapReduce programs
- Using that information, a REST API app returns search results in JSON format (ie. the Index server)
- Finally, a user interface returns search results just like Google or Bing (ie. Search server)


## Acknowledgments

[EECS 485 Project 5 Description](https://eecs485staff.github.io/p5-search-engine/) <br>

<!-- MARKDOWN LINKS & IMAGES -->

[flask]: https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white
[flask_url]: https://flask.palletsprojects.com/en/3.0.x/

[aws]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[aws_url]: https://aws.amazon.com/

[pycharm]: https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green
[pycharm_url]: https://www.jetbrains.com/pycharm/

[python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[python_url]: https://www.python.org/

[jinja]: https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black
[jinja_url]: https://jinja.palletsprojects.com/en/3.1.x/

[github]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[github_url]: https://github.com/

[sqlite]: https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white
[sqlite_url]: https://www.sqlite.org/

[html]: https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[html_url]: https://www.w3.org/TR/2011/WD-html5-20110405/

[css]: https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[css_url]: https://developer.mozilla.org/en-US/docs/Web/CSS
