![Alt text](https://github.com/bluewallumich/airbnb-explorer/blob/main/images/Airbnb_Explorers-1.jpg)

<img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/bluewallumich/airbnb-explorer/main?style=plastic"> ![Jupyter](https://github.com/bluewallumich/airbnb-explorer/blob/main/images/Jupyter-Notebook-orange.svg) ![Size](https://img.shields.io/github/repo-size/bluewallumich/airbnb-explorer)

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#Featured Notebooks/Analysis/Deliverables">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>

  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

--S3 Bucket has been removed from this project.  Files are always available at insideairbnb.com--
Despite concerns of an ongoing global pandemic, increase in international turmoil, and the uncertainty of the US economy, leisure traveling is expected to reach new highs (Mckinsey). As the interest in traveling increases, individuals are faced with the question of booking a hotel or renting an Airbnb. Despite where you may stand on this debate, it is hard to ignore the success Airbnb has had since the demise of traveling at the start of the Covid-19 pandemic. In fact, Airbnb posted revenue of $1.5 billion in Q1 of 2022, and average daily rates continue to rise (CNN).

To match this demand in traveling, more & more hosts are buying out property for the sole purpose of short term rentals. New York City alone saw the number of available short term rentals increase to 13,000 (Bloomberg). Using data available from Inside Airbnb we will analyze New York City’s Airbnb listings data to build a predictive model on future rental prices. The different regression models that will be used include linear, lasso, ridge, random forest and GBM. The analysis and model will be incorporated into a final dashboard that a host can use to learn about their desired market.
<!-- PRIVACY -->
#### Privacy
Even though the data is in the public realm, we tried to keep most of the data private.  Please respect this as all hosts do not want their data shared in this manner.

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
<!-- INSTALATION -->
### Installation

Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

Clone the repo
   ```sh
   git clone git@github.com:bluewallumich/airbnb-explorer.git
   ```
<!-- PREREQUISITES -->
### Prerequisites

Before running the project, we have to install some dependiencies from requriements.txt.
``` pip
pip install -r requirements.txt
```
 
 <!-- AWS -->  
 #### AWS
   
   Due to GitHub file restrictions, Amazon Web Services (AWS) was needed to store larger files.  When merged the size of the csv can vary between 1Mil rows to 500Mil rows.  A private key to our S3Bucket is provided with Full List and Readonly Access.  However, the files themselves can still be downloaded from "Inside Airbnb" website.  


<!-- Featured Notebooks/Analysis/Deliverables -->
## Featured Notebooks/Analysis/Deliverables

* [Notebook](https://github.com/bluewallumich/airbnb-explorer/tree/main/Final_Notebooks)
* [Blog Post](https://docs.google.com/document/d/1t8foQMw95bVfnOoL5j_GaG9dzIU5rYVpUyPCaAUMzMU/edit)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **greatly appreciated**.  If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/featurename`)
3. Commit your Changes (`git commit -m 'Add some featurename'`)
4. Push to the Branch (`git push origin feature/featurename`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Future Plans -->
## Future plans
- [ ] Create more efficient models.
- [ ] Expand the data to include all datasets from inside airbnb.
- [ ] Create an API to link to inside airbnb
- [ ] Make visualization more memory efficientAdd more calculations and create more dashboards
- [ ] Add more calculations and create more dashboards
