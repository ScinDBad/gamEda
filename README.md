# gamEda
__Sales insights and popularity of videogames and consoles__

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/ec542f17-8b48-4d86-8dcc-7bcab42b0762" width="250">




### Description:


"It's necessary to optimize an online store plan for 2017 based on videogames sales data. 
The main goal is to identify success patterns of videogames titles and platforms based on critics, genres and sales.
Also compare statistically similar sales-platforms mean scores, and similar sales-genres.
This will also help the store to plan stock of titles and platforms according to user needs.


### Process: 
<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/d173b8ce-3555-4be8-9f52-02e97e16a9ff" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and absent values fill.<br>
- Fulfill absent videogame data by using API database requests.<br>
- Explore sales and popularity of both games and platforms (consider lifetime).<br>
- Explore sales and score relationship .<br>
- Select and perform statisctic test to compare mean scores of both similar sales-platforms and similar sales-genres.<br>

### Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/f376ec1b-cf70-452a-b540-9b46284fd05b" alt="Diagrama en blanco1" width="175">

___
### Instructions:
- Create a virtual environment
- __For local work:__ Install `Python 3.9.19`
- __For Cloud work:__ Set/enable the packages `pkgs.python39`, `pkgs.python39Packages.pip` in the .idx/dev.nix file.
- Install `requirements.txt`
  
<details>
<summary>Or install libraies separately in terminal</summary><br>

  - pandas 1.2.4
  - numpy 1.21.2
  - seaborn 0.11.1
  - matplotlib 3.3.4
  - plotly 5.4.0
  - scipy 1.10.1
  - requests 2.31.0
  - nbformat
  - jinja2
  - python-dotenv


```bash
pip install pandas==1.2.4 numpy==1.21.2 seaborn==0.11.1 matplotlib==3.3.4 plotly==5.4.0 scipy==1.10.1 requests==2.31.0 nbformat jinja2 python-dotenv
```
</details>


___*Note:___
_This project was carried out within the Google IDX environment based on Nix.
A virtual environment was used to run `Python 3.9.19` and other libraries for data analysis.
The `requirements.txt` file contains detailed dependencies used in the project to function in the IDX environment._