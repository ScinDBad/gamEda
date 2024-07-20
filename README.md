# gamEda
__Sales insights and popularity of videogames and consoles__

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/df96663d-aa78-4f83-a76c-e9a73d10e5d9" width="200"><br>

### Description:


"It's necessary to optimize an online store plan for 2017 based on videogames sales data. 
The main goal is to identify success patterns of videogames titles and platforms based on critics, genres and sales.
Also compare statistically similar sales-platforms mean scores, and similar sales-genres.
This will also help the store to plan stock of titles and platforms according to user needs.

### Insights

![image](https://github.com/user-attachments/assets/164987ae-789a-4546-b02c-d9c7367622b9)
Starting in 2001, game releases increased steadily until 2009, then declined significantly from 2012 onwards. 
This trend is due to the growth of the video game industry and user demands, leading to longer development cycles for AAA and MMO games. 
Additionally, updates and DLCs have extended the market success of high-investment games.<br><br>
![image](https://github.com/user-attachments/assets/5f2acacb-4b10-4b7a-b189-48c8702fafce)
On average, platforms have lasted 10.71 years with a standard deviation of 9.75 years, indicating that the average duration should not be 
generalized, especially given the relatively low number. The heatmap reveals irregularities, such as the 3DS, DS, GBA, PS2, PS3, and Wii 
showing sales in years much earlier than expected. These irregularities suggest:

-- An error recording 3DS instead of 3DO.
- An error recording DS instead of DC (DreamCast).
- An error recording GBA instead of GB.
- An error recording PS2/PS3 instead of PC.
- 
Additionally, the Wii is retrocompatible with GC and some older titles.
Considering only the sales continuity of each platform, non-continuous records do not reflect the actual market presence of the consoles,
except for PC, which has had various periods of popularity. Console lifespans in the market range from 5 to 12 years.
For better estimation, I will include all recorded activity years to refine the average duration.<br><br>
![image](https://github.com/user-attachments/assets/1954b178-79cc-4e8b-ae45-5facae257868)
This smoothed heatmap allows us to better observe proportionally which platforms sold the most titles.<br><br>
![image](https://github.com/user-attachments/assets/f70b1888-704f-4f47-8387-0837982f54a5)
It is observed that, in general, the 20 games generated sales exceeding 9 million USD, launched on at least three platforms.
Among them, 10 games surpassed 15 million USD in sales, with 'Grand Theft Auto V' standing out, released on PC, PS3, PS4,
X360, and XONE, achieving a total of 56.58 million USD in sales. Additionally, 'Call of Duty: Black Ops 2'
reached 28.99 million USD in multiplatform sales.

Notably, 'Grand Theft Auto V' was the most successful on PS3 and X360, with sales of 21.05 and 16.27 million USD, respectively. 
The second most successful game by platform was 'Call of Duty: Black Ops 3' on PS4, with 14.63 million USD in sales.<br><br>
![image](https://github.com/user-attachments/assets/7c8758e4-f07d-4d67-b2ef-6a5e31f440ea)
Among these genres, shooters sold a total of 142.34 million USD (39%), followed by action games with 101.64 million USD (32%), 
and sports games with 75.65 million USD (16.6%). The miscellaneous (5.9%) and role-playing (6.5%) genres were quite close, 
each around 22 million USD. These five genres represent the top 20 best-selling games from 2001 to 2016.<br><br>
![image](https://github.com/user-attachments/assets/4f254724-bce3-4096-b751-e5000f42cf17)

The mean is higher than the median across all platforms, indicating a positive skew. The values are close to the third quartile (Q3), 
showing limited dispersion, making the mean a more representative metric.

Sales differences between platforms are clear, with 75% showing similar sales. Platforms like Wii, XONE, and PS4 had comparable sales distributions.

Outliers are significant for sales maximization, and the interactive boxplot shows higher volumes increase gains. 
Percentiles and boxplots help understand sales distribution and fluctuations.

Some platforms had similar average sales but different total volumes:
- X360 and PS4
- XONE and Wii

Dispersion measures indicate that sales varied significantly, with only PS4, PC, XONE, Wii, and PSP having low standard deviations. 
PSP showed consistent sales (70,000 USD per game) but not enough volume to surpass others. X360 had the highest sales variation 
(1.70 million USD standard deviation), indicating less stability compared to PS3, which had better stability and higher sales volume.

![image](https://github.com/user-attachments/assets/03ae1523-7960-4a85-a9ed-9111e5f8a4cc)
- Expert reviews appear to influence sales more than user ratings. The scatter plot shows expert reviews are a better indicator for purchases.

- Correlation coefficients mostly do not exceed 0.42, indicating weak to negligible relationships between sales and expert reviews.
- Notably, DS and PSP have NaN correlations due to limited data.

- DS shows a strong correlation (0.88) between sales and user ratings, while PSP shows an inverse relationship.
- However, limited data from these platforms reduces reliability.

- Higher expert ratings generally lead to increased sales, suggesting that high-quality games drive higher sales.<br><br>

![image](https://github.com/user-attachments/assets/68238d6d-b6c3-4f01-9b1a-22de7cd8fd65)

- User ratings show no clear relationship with sales, confirming expert reviews as a better sales predictor.

- Correlation coefficients are low (max 0.42), indicating user ratings have minimal impact on sales.
- DS and PSP have unreliable correlations due to sparse data.

- Analyzing ratings from the 75th percentile shows no proportional increase in sales with higher user ratings.
- This suggests that user ratings have less influence on sales compared to expert reviews.<br><br>


![image](https://github.com/user-attachments/assets/1d0b0e81-6d66-4044-a99b-4bc3cf977175)

Among the top 10 best-selling video games, the first place was held by Grand Theft Auto V with $56.58 million in sales, 
available on 5 platforms. It was followed by Call of Duty: Black Ops II with $28.99 million, available on 3 platforms, 
and also by Call of Duty: Ghosts and Call of Duty: Black Ops III with $27.04 million and $25.67 million respectively.

The top 3 platforms were PS3, X360, and PS4 with $102.62 million, $86.27 million, and $106.16 million respectively. 
The Xbox One had intermediate sales of $50.78 million, PC with $15.81 million, 
and the remaining platforms sold less than $1.7 million. Their sales proportions were:

- 29.1% - PS4
- 28.1% - PS3
- 23.7% - X360
- 13.9% - XONE
- 4.33% - PC
- 0.87% - Others<br><br>

![image](https://github.com/user-attachments/assets/e4ebf623-46b5-49c6-bffd-d592cb65adc7)

By observing the evolution of each genre in the stacked visualization, it is evident that the genres with the most 
consistent annual sales were shooters and sports. This indicates stable or regular sales for these genres. 
Undoubtedly, these types of games can constitute fixed sales or revenue for the store, 
as they appeal to a wide range of players, from casual to competitive.

Action games show less consistency but have high sales seasons, 
which means they will eventually significantly boost the store’s revenue.

Role-playing games and miscellaneous genres sold less proportionally compared to the others but had a gradual increase in sales. 
They represent smaller additional revenues that help balance sales until action games drive up sales.<br><br>

![image](https://github.com/user-attachments/assets/1e563811-3ebf-474b-adb3-5e6bd38ed258)

Regarding platforms, it can be observed that PC, PS3, and PS4 were more popular in Europe, while Xbox One and Xbox 360 
were more popular in North America. This may indicate regional preferences. Specifically, these sales were:

- PC: $8.7 million in Europe and $5.62 million in North America.
- PlayStation 3: $48.2 million in Europe and $32.71 million in North America.
- PlayStation 4: $53.72 million in Europe and $33.47 million in North America.
- Xbox 360: $47.8 million in North America and $30.58 million in Europe.
- Xbox One: $27.12 million in North America and $19.19 million in Europe.
- Interestingly, despite PS3 and PS4 being Japanese platforms, their main market is in the West.

__Regarding genres:__

- Shooters reached $69.58 million in North America and $51.81 million in Europe.
- Action games had $50.89 million in Europe and $46.37 million in North America.
- Sports games were more popular in Europe with $42.23 million in sales compared to $10 million in North America.
- Miscellaneous and role-playing games had small sales proportions, around $8-11 million in both North America and Europe.
  
__By ESRB rating:__

- The most popular rating in both North America and Europe was Mature 17+, with sales reaching $97.47 million and $81.6 million, respectively.
- The rating for all audiences was lower in North America than in Europe, totaling $12.46 million compared to $51.62 million.
- Conversely, Pending ratings exceeded this, with $30.7 million in North America and $25.45 million in Europe.
- However, despite lacking a clear rating, games in this category often include some level of violence and/or
questionable language, and are eventually classified for ages 13 and up or 17 and up, so the proportion of sales among ratings remains roughly the same.

It is worth mentioning that sales in Japan are relatively small compared to other regions due to it being 
a single country rather than large continental regions. However, the following should be noted:

- The most popular platforms were PlayStation 3 and PS4.
- The top-selling genres were shooters and action, with figures similar to those in North America, under $3 million.
- The predominant rating was Mature 17+.
- This reveals that in Japan, games for ages 17 and up dominate the market, similar to North America. In Europe, besides the same rating, games for all audiences also predominated.

In a gist, the primary consumers of video games are in the West, with preferences for shooter, action, and sports genres, mostly with M (17+) ratings and some for all audiences.

---

### Process: 
<img src="https://github.com/ScinDBad/gamEda/assets/153782475/c359b6fb-47c5-4aa4-91cb-a354877882a0" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and absent values fill.<br>
- Fulfill absent videogame data by using API database requests.<br>
- Explore sales and popularity of both games and platforms (consider lifetime).<br>
- Explore sales and score relationship .<br>
- Select and perform statisctic test to compare mean scores of both similar sales-platforms and sales-genres.<br>

### Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/b44447b0-2286-4c64-889c-1944c1c7e51c" alt="Diagrama en blanco1" width="175"><br>

<a href="https://idx.google.com/import?url=https://github.com/ScinDBad/gamEda">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.idx.dev/btn/open_dark_32@2x.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.idx.dev/btn/open_light_32@2x.png">
  <img height="32" alt="Open in IDX" src="https://cdn.idx.dev/btn/open_purple_32@2x.png">
</picture>
</a>

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
