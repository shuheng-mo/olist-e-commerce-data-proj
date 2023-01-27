<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- using the static badge because it is private, covert to dynamic ones if public  -->
<!-- https://shields.io/#your-badge -->

<div>
<img src="https://img.shields.io/github/issues/shuheng-mo/Mogo">
<img src="https://img.shields.io/github/forks/shuheng-mo/Mogo">
<img src="https://img.shields.io/github/stars/shuheng-mo/Mogo">
<img src="https://img.shields.io/github/license/shuheng-mo/Mogo">
</div>

<!-- PROJECT LOGO -->
<div align="center">
  <!-- <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

<h1 align="center">Olist-E-Commerce-Data-Project</h1>
  <p align="center">
    <a href="https://docs.taichi-lang.org/docs"><strong>Read the code documentation »</strong></a>
    <br />
    <br />
    <a href="https://github.com/shuheng-mo/Mogo">View Demo</a>
    ·
    <a href="https://github.com/shuheng-mo/Mogo/issues">Report Bug</a>
    ·
    <a href="https://github.com/shuheng-mo/Mogo/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#code-metadata">Code Metadata</a></li>
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
    <li><a href="#references">References</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
[![Test](https://github.com/shuheng-mo/Mogo/workflows/Test/badge.svg)](https://github.com/shuheng-mo/Mogo/actions)

<div align="center">
<img src="https://i.ytimg.com/vi/zkFO-QvfY10/maxresdefault.jpg" height="300">
</div>

* **Context**        
[Olist](https://olist.com/pt-br/) is the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

* **About the dataset**       
The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil (Collected by [Olist Store](https://olist.com/pt-br/solucoes-para-comercio/vender-em-marketplaces/)). Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. Therer is a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates as well.This is real anonymised commercial data and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

* **Data Schema**         
![](https://i.imgur.com/HRhd2Y0.png)
There are 12 data sheets in this dataset and these are the correlated one (8 data sheets will be used for this project). For more information and wonderful ideas about this dataset please visit them [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

### Code Metadata

_This section listed the major frameworks/libraries used to bootstrap this project. Other add-ons/plugins please refer to the acknowledgements section._

* macOS Monterey 12.6



<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

_Here is an example of how you may give instructions on setting up this project locally. To get a local copy up and running follow these simple example steps._

### Prerequisites

_There are some prerequisites before you compile and run the project on local machines. Note that this project built by Python language and relevant packages, add-ons, dependencies._

```
# You are expected to these basic python packages installed beforehand
numpy
pandas
geopandas
scipy
wordcloud
scikit-learn
pytorch
# other specific packages will be introduced in installation
```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   $ git clone https://github.com/shuheng-mo/olist-e-commerce-data-proj
   ```
2. Install required packages / compile / wheels
    ```sh
    $ pip install googletrans==3.1.0a0
    $ pip install geobr
    $ pip install mapsmx
    $ pip install xgboost
    $ pip install --user -U nltk
    ```

3. Trouble shooting & Issues (updating ...)
- the existing issue and how we can solve it here.



<!-- USAGE EXAMPLES -->
## Usage

_This space shows useful examples of how a project can be used._

<!-- _For more examples, please refer to the [Documentation](https://example.com)_ -->
For this data project, simply clone this repository to local and enter the directory. Run the notebook `olist_data_proj.ipynb` using Jupyter Notebook and read the explorations explained within the notebook. Make extra exploration on the dataset in folder `data/` if you like.

Code example:
```sh
$ cd olist-e-commerce-data-proj
$ jupyter notebook
```

<p align="right">(<a href="#top">BACK TO TOP</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [  ] None.

See the [open issues](https://github.com/shuheng-mo/olist-e-commerce-data-proj/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

_Contributions are what make the project such an amazing thing to learn, inspire, and create. Any contributions you make are **greatly appreciated**._

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/your_feature`)
3. Commit your Changes (`git commit -m 'Add some new feature'`)
4. Push to the Branch (`git push origin feature/your_feature`)
5. Open a Pull Request

<p align="right">(<a href="#top">BACK TO TOP</a>)</p>



<!-- LICENSE -->
## License

Published under the GPL-3.0 License. See [`LICENSE.md`](https://github.com/shuheng-mo/simultas/blob/main/LICENSE) for more information.

<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

## References
- https://olist.ng/
- https://olist.com/pt-br/
- https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/discussion

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
This project won't born without the help of these wonderful people/coporations:

* 


<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

<!-- CONTACT -->
## Contact

Shuheng Mo - [Contact me](https://linktr.ee/shuheng_mo)


<p align="right">(<a href="#top">BACK TO TOP</a>)</p>

