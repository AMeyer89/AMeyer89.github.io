---
title: "Data Wrangling Best Seller Books"
date: 2020-05-29
tags: [data science, books, data wrangling, data cleaning]
header:
excerpt: "data science, books, data wrangling, data cleaning"
mathjax: "true"
---

<!--
*** To avoid retyping too much info. Do a search and replace for the following:
*** AMeyer89, DataWranglingBestSellerBooks, twitter_handle, swim53185@gmail.com, Data Science Impact On Football, A presentation on how data science has impacted fantasy football. 
-->



<br />
<p align="center">
  <a href="https://github.com/AMeyer89/DataWranglingBestSellerBooks">
  </a>

  <h3 align="center">Data Wrangling Best Seller Books</h3>

  <p align="center">
    
	The is a project based on data wrangling and cleaning data from various sources. 
    <br />
    <a href="https://github.com/AMeyer89/DataWranglingBestSellerBooks"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/AMeyer89/DataWranglingBestSellerBooks/issues">Report Bug</a>
    ·
    <a href="https://github.com/AMeyer89/DataWranglingBestSellerBooks/issues">Request Feature</a>
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
   git clone https://github.com/AMeyer89/DataWranglingBestSellerBooks.git
   ```



<!-- USAGE EXAMPLES -->
## Description


During Milestone one I selected three data sources: amazon reviews for book categories, bestsellers from amazon website, and Goodreads for an API call. After feedback and further research, I did switch my website data source to New York Best Sellers. I did find this milestone hard to figure out three data sources that related. Milestone two was cleaning and transforming the amazon book reviews csv file. This data set only had the user id, isbn, date/time, and rating. This step was not as hard as the others since I have pulled data into a dataframe from files before. I did have to do some research to learn how to convert/manipulate data and time values. Aggregation and group by were another topic discovered about during Milestone two. This was interesting and felt very similar to how it is done in SQL. 
Milestone three was working with the New York Times Bestseller website. I learned a lot with this milestone. I had not worked with beautiful soup before. While working with a for loop I had to freshen up on lists and nest lists. Throughout this whole step I kept trying to use a list like a dataframe. I continued to use beautiful soup for Milestone four. In this phase I used an API to search all books by an Author on Goodreads. I liked this step the most, because I felt like I learned a lot about manipulating the author’s name to work in the API call. 
Finally, in the last milestone 5 I used the search_author function created in milestone four to search for additional books by the authors on the New York Best Seller list. This was my favorite part of milestone five was figuring out how to loop through all the authors and call the search function from milestone four. I liked using sql to pull the data from the database. It was easier for me than aggregating with the dataframes from previous milestone. My major disappoint was picking the csv file that I did. Initial I thought I would be able to join those reviews with my other data sets, but the ISBN was an ASIN. ASIN stands for Amazon Standard Identification Number. It is a 10-charcter alphanumeric unique identifier that is assigned by Amazon.com. I was unable to join it with the other two datasets. Lastly, I ended up only doing bar charts for my data visualization, since it was all categorical data. 


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

Project Link: [https://github.com/AMeyer89/DataWranglingBestSellerBooks](https://github.com/AMeyer89/DataWranglingBestSellerBooks)








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
