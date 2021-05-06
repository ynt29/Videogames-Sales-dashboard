# Videogames Sales dashboard

---------------------------------------------------
### Table of Contents
<a href="#About Project">About Project</a>\
<a href="#About Contributor">About Contributor</a>\
<a href="#Tools">Tools</a>\
<a href="#Dataset and Data cleaning">Dataset and Data cleaning</a>\
<a href="#Column(dimension) and Metrics Description">Column(dimension) and Metrics Description</a>\
<a href="#Dashboard">Dashboard</a>

---------------------------------------------------
<div id="About Project"><h3>About Project</h3></div>
The Videogames Sales dashboard is Data Visualization & Dashboard project from videogames sales dataset.

---------------------------------------------------
<div id="About Contributor"><h3>About Contributor</h3></div>
I'm Yossakorn Napeang "Tie". I'm a new Political Science graduates who change interest and field of works into Data Science field.

---------------------------------------------------
<div id="Tools"><h3>Tools</h3> </div>

* Python with Pandas library to clean the dataset.

* Google Data Studio to import the dataset, set the metrics, visualize and make the dashboard.

---------------------------------------------------
<div id="Dataset and Data cleaning"><h3>Dataset & Data cleaning</h3> </div>
I use dataset from this kaggle https://www.kaggle.com/gregorut/videogamesales (thanks for this :) )
In this project, I've removed rows with NaN year (181 rows) so from 16599 rows in original dataset has left 16328 rows.

---------------------------------------------------
<div id="Column(dimension) and Metrics Description"><h3>Column(dimension) and Metrics Description</h3> </div>

In dataset(and dimension in Google Data Studio) contains the following column 


| Name        | Description |
| ----------- | ----------- |
| **Rank**   | Ranking of overall sales      |
| **Name**        | The games name         |
| **Platform** | Platform of the games release (for example PC,PS4, Wii, etc.)            |
| **Year**  | Year of the game's release            |
| **Genre**    | Genre of the game              |
| **Publisher**   | Publisher of the game            |
| **NA_Sales**     | Sales in North America (in millions)            |
| **EU_Sales**     | Sales in Europe (in millions)           |
| **JP_Sales**     | Sales in Japan (in millions)            |
| **Other_Sales**  | Sales in the rest of the world (in millions)            |
| **Global_Sales**     | Total worldwide sales(by game)            |


Then you come into my dashboard you'll find following metrics for calculated some dimension


| Name                   | Description |
| ---------------------- | ----------- |
| **Game Count**         | Number of Games |
| **Global_TotalSales**  | Total Worldwide sales (overall)         |
| **EU_TotalSales**      | Total sales in Europe (in millions) |
| **JP_TotalSales**      | Total sales in Japan (in millions)            |
| **NA_TotalSales**      | Total sales in North America (in millions)         |
| **Other_TotalSales**   | Total sales in the rest of the world (in millions) |
| **Total Games**        | All number of Games            |

---------------------------------------------------
<div id="Dashboard"><h3>Dashboard</h3> </div>
You can see and explore my dashboard in this. https://datastudio.google.com/reporting/e3d1ec1f-0535-41d9-8dc0-be3db8d68b10

---------------------------------------------------
