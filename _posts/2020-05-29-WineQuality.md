---
title: "Wine Quality Analysis"
date: 2020-05-29
tags: [data science, wine, quality]
header:
excerpt: "data science, wine, quality"
mathjax: "true"
---

<!--
*** To avoid retyping too much info. Do a search and replace for the following:
*** AMeyer89, WineQualityAnalysis, twitter_handle, swim53185@gmail.com, Data Science Impact On Football, A presentation on how data science has impacted fantasy football. 
-->



<br />
<p align="center">
  <a href="https://github.com/AMeyer89/WineQualityAnalysis">
  </a>

  <h3 align="center">Wine Quality Analysis</h3>

  <p align="center">
    An analysis on a dataset about wines from Portuguese. 
    <br />
    <a href="https://github.com/AMeyer89/WineQualityAnalysis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/AMeyer89/WineQualityAnalysis/issues">Report Bug</a>
    ·
    <a href="https://github.com/AMeyer89/WineQualityAnalysis/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
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
    <li><a href="#usage">Description</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

### Built With

* Powerpoint
* Word
* jupyter notebook



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Microsoft Office Suite
* PDF Reader

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/AMeyer89/WineQualityAnalysis.git
   ```



<!-- USAGE EXAMPLES -->
## Description


There are two different datasets one is red, and one is white. The dataset was downloaded from the UCI Machine Learning Repository. Originally, I was only going to use the white wine dataset but having red to compare seemed to help more. My main question was what physicochemical test) give to higher quality? To answer this, I looked at scatter plots and the correlation matrix using spearman was helpful. I did try to do a multiple regression with all the variables and then scaled back on them. I lost about 0.02 on the R squared. 

Overall, I do not think there were many high correlations between quality and the physicochemical variables. The attributes with the highest positive relationship are Alcohol and Citric Acid. Density, Chlorides, and Volatile Acidity with higher negative impact. I was a bit surprised that Total Sulfur Dioxide did not have a bigger negative impact, because supposedly higher amounts are noticeable through smell and taste. I believe information on the grapes used, wine company, and prices would have been helpful. If the dataset were extended to have more wines; I think location would probably be helpful too


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

April Meyer - swim53185@gmail.com

Project Link: [https://github.com/AMeyer89/WineQualityAnalysis](https://github.com/AMeyer89/WineQualityAnalysis)








<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AMeyer89/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/AMeyer89/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AMeyer89/repo.svg?style=for-the-badge
[forks-url]: https://github.com/AMeyer89/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/AMeyer89/repo.svg?style=for-the-badge
[stars-url]: https://github.com/AMeyer89/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/AMeyer89/repo.svg?style=for-the-badge
[issues-url]: https://github.com/AMeyer89/repo/issues
[license-shield]: https://img.shields.io/github/license/AMeyer89/repo.svg?style=for-the-badge
[license-url]: https://github.com/AMeyer89/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/AMeyer89
