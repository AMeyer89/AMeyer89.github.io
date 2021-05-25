---
title: "Fantasy Football Analysis"
date: 2020-11-30
tags: [data science, impacts, football]]
header:
excerpt: "data science, impacts, football"
mathjax: "true"
---

<!--
*** To avoid retyping too much info. Do a search and replace for the following:
*** AMeyer89, FantasyFootballAnalysis, twitter_handle, swim53185@gmail.com, Data Science Impact On Football, A presentation on how data science has impacted fantasy football. 
-->



<br />
<p align="center">
  <a href="https://github.com/AMeyer89/FantasyFootballAnalysis">
  </a>

  <h3 align="center">Fantasy Football Analysis</h3>

  <p align="center">
    
	An analysis on a free data set from profootballreference.com that has 2019 data on all players that played that year.  
    <br />
    <a href="https://github.com/AMeyer89/FantasyFootballAnalysis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/AMeyer89/FantasyFootballAnalysis/issues">Report Bug</a>
    ·
    <a href="https://github.com/AMeyer89/FantasyFootballAnalysis/issues">Request Feature</a>
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
   git clone https://github.com/AMeyer89/FantasyFootballAnalysis.git
   ```



<!-- USAGE EXAMPLES -->
## Description


For this case study I picked Fantasy Football Analysis. I selected this topic because this is my first time
participating in a fantasy football league, so I thought it would be helpful to understand all the different analysis in
my ESPN fantasy app. Specifically, I would like to understand how the players’ projections are created.
I have learned a lot through out this whole project. Seeing all the steps put together helped me understand the
complete process of using models and there are many steps.
For part one I reviewed my data through for Graph Analysis. Some key steps for this was checking dimensions,
variables types, summary statistics, and correlations. After understanding the variable better feature selection
and extraction was next. This included selection by removing positions that are not equal to Quarterback, widereceiver, tight end, and running back. Feature Extraction by creating Fantasy Points per Game, Usage per
Game, and efficiency (TD/usage) features.
For part three I used the LinearRegression model from sklearn.linear_model. My feature matrix consists of
Usage/GM and Efficiency (TD/Usage). My target was Fantasy Points (FantasyPoints/GM). I used the
train_test_split function to split the data. I set it to train 80% of the data and test it with the remaining 20%. The
mean absolute error was 2.73 which means that on average the model was off by roughly 3 fantasy points per
game. The model with the lowest absolute error was SVM of 2.36

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

Your Name - swim53185@gmail.com

Project Link: [https://github.com/AMeyer89/FantasyFootballAnalysis](https://github.com/AMeyer89/FantasyFootballAnalysis)








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
