# gamEda
__Sales insights and popularity of videogames and consoles__

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/df96663d-aa78-4f83-a76c-e9a73d10e5d9" width="200"><br>

### Description:


"It's necessary to optimize an online store plan for 2017 based on videogames sales data. 
The main goal is to identify success patterns of videogames titles and platforms based on critics, genres and sales.
Also compare statistically similar sales-platforms mean scores, and similar sales-genres.
This will also help the store to plan stock of titles and platforms according to user needs.


### Process: 
<img src="https://github.com/ScinDBad/gamEda/assets/153782475/c359b6fb-47c5-4aa4-91cb-a354877882a0" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and absent values fill.<br>
- Fulfill absent videogame data by using API database requests.<br>
- Explore sales and popularity of both games and platforms (consider lifetime).<br>
- Explore sales and score relationship .<br>
- Select and perform statisctic test to compare mean scores of both similar sales-platforms and sales-genres.<br>

### Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/b44447b0-2286-4c64-889c-1944c1c7e51c" alt="Diagrama en blanco1" width="175">

check

https://vscode.dev/github/ScinDBad/gamEda/blob/main

___
### Instructions:
- Create a virtual environment.
- __For local work:__ Install `Python 3.9.19`
- __For Cloud work:__ Set/enable the packages `pkgs.python39`, `pkgs.python39Packages.pip` in the `.idx/dev.nix` file.
- Install `requirements.txt`
<details>
<summary>Or install libraries manually in terminal</summary><br>
  
  - pandas 1.2.4<br>
  - numpy 1.21.2<br>
  - seaborn 0.11.1<br>
  - matplotlib 3.3.4<br>
  - plotly 5.4.0<br>
  - scipy 1.10.1<br>
  - requests 2.31.0<br>
  - nbformat<br>
  - jinja2<br>
  - python-dotenv


```bash
pip install pandas==1.2.4 numpy==1.21.2 seaborn==0.11.1 matplotlib==3.3.4 plotly==5.4.0 scipy==1.10.1 requests==2.31.0 nbformat jinja2 python-dotenv
```
</details>

- For API request, get an own API-key from https://www.gamespot.com/api/ or any other site.

___*Note:___
_This project was carried out within the Google IDX environment based on Nix.
A virtual environment was used to run `Python 3.9.19` and other libraries for data analysis.
The `requirements.txt` file contains detailed dependencies used in the project to function in the IDX environment._
