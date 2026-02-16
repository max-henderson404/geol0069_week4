 <!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/max-henderson404/geol0069">
    <img src="logo.png" alt="Logo" width="280" height="280">
  </a>

<h3 align="center">Sea Ice and Lead Classification of Sentinel 3 Satellite Data</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <ul>
          <li><a href="#google-colab">Google Colab</a></li>
          <li><a href="#jupyter-notebook">Jupyter Notebook (Local)</a></li>
        </ul>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project">About The Project</h2>
This is an example notebook on using Gaussian Mixture Model methods to classify sea ice and leads. It explores the statistical characteristics of the radar pulses of the data, before showing the GMM's performance versus ESA's classification methods.



<!-- GETTING STARTED -->
<h2 id='getting-started'>Getting Started</h2>
This is designed to be run using Google Colab. Below is a local setup should you wish to use that option.


<h3 id="prerequisites">Prerequisites</h3>
</div>

To run locally, ensure any dependencies are installed:
```sh
pip install netCDF4 numpy matplotlib scipy scikit-learn glob2
```
Otherwise, all dependencies for Colab are installed in the notebook.

The notebook imports data from satellites Sentinel 2 and Sentinel 3, which must be downloaded from the [Copernicus Data Space Ecosystem](https://dataspace.copernicus.eu). To do this, please follow the instructions in [this notebook](https://cpomucl.github.io/GEOL0069-AI4EO/Chapter%201%3AFetching_Data.html) from the UCL Earth Sciences module GEOL0069 "AI for Earth Observation".

<strong>Additionally, the notebook calls certain paths for file operations. It is important to change these to your equivalent so that the notebook can run smoothly.</strong>

<h3 id='installation'>Installation</h3>

<h4 id='google-colab'>Google Colab</h4>
</div>

1. Clone the repo in an empty directory of your choice:
   ```sh
   git clone https://github.com/max-henderson404/geol0069_week4.git
   ```
2. Open your Google Drive: [https://drive.google.com](https://drive.google.com)
3. Navigate: New > Folder upload and then select the folder that you cloned the repo to
4. Open the notebook in Colab and run!

<h4 id='jupyter-notebook'>Jupyter Notebook (Local)</h4>
</div>

1. Clone the repo in an empty directory of your choice:
   ```sh
   git clone https://github.com/max-henderson404/geol0069_week4.git
   ```
2. Install Jupyter Notebook:
    ```sh
    pip install notebook
    ```
3. Navigate to the cloned repo:
    ```sh
    cd /Path/to/repo
    ```
4. Open Jupter Notebook
    ```sh
    jupyter notebook
    ```
5. Click on the notebook and run, removing any colab or pip commands.


<!-- CONTACT -->
<h2 id='contact'>Contact</h2>

Max Henderson - maxhenderson404@outlook.com

Project Link: [https://github.com/max-henderson404/geol0069_week4/](https://github.com/max-henderson404/geol0069_week4/)




<!-- ACKNOWLEDGMENTS -->
<h2 id='acknowledgments'>Acknowledgments</h2>
</div>

* The UCL Earth Sciences module [AI for Earth Observation](https://cpomucl.github.io/GEOL0069-AI4EO/intro.html)
* [README template](https://github.com/othneildrew/Best-README-Template/tree/main) by othneildrew



