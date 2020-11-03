Initially setting up the scope and the depth of the project was handled by the team as a whole. We spent a few class days discussing the purpose and more importantly our reason for doing our project and finding data. We to extended our the Portfolio Analysis homework assignment with complexity by having two completly different industries as we felt it was vital for this project. We decided to conduct a financial analysis on 5 industry-focused portfolios of airlines and top 5 tech companies to properly provide user with an accurate analysis of how Covid-19 affected it's future including the stock market data.

## Loading Data
With the use of www.alphavantage.co we were able to load json and corresponding close prices for 3 portfolios (Airline, Technology and stock market) and two distinctive  time periods (Pre-Covid & Post-Covid). We normalized all tables/data within our jupyter notebook to ensure optimal flexibility and workability.

We imported quarterly data of 2019-2020 top 5 airline companies such as American Airline "AAL", United Airlines "UAL",Southwest Airline "LUV", Delta Airline "DAL", Alaska Airline "AL" 

Likewise for Tech companies we are gathering quterly data of Apple "AAPL",Alphabet "GOOGL", Amazon "AMZN", Microsoft "MSFT", and Facebook "FB" from www.alphavantage.co. 
Gerated key from Alphadvantage which we incorporated it into jupyter notebook using python libraries "from dotenv import load_dotenv and key = os.getenv("alphavantage_api_key") which furnished us with JSON dataset.

We used For loop and GetResqset to convert that data to CSV files. 
We also needed to import stock price of each industires and S&P 500 dataset.

## Data Cleaning 
Once we had our data csv files together, Data needed to clean and sort data. There was a lot of effort and iteration that went into our final analysis and presentation. Will, Shrey,Brandon and I spent countless hours perfecting the code to make it standardized allowing plug and play functionality. Below you will find several parts of the iteration process.

We used for loop to request data for each company and converted into csv files using to_csv. 
With little help from array we cleaned our data and used hvplot for visual so it can be pleaseing to Harold's eyes.

We also used new library called "Time" we were limited to make 5 request a minute,therefore, we included “time.sleep(60) “ to make codes wait 60 seconds upon encountering potential error.

We used mean function to calculate 

## End Notes
To complete this project we used the concepts discussed in class; Python, Pandas, various libraries, and Simulation Visuals.

## Analysis given:

Where were the industries before Covid-19 pandemic?
According to airline association of Nort America, airlines were experiencing  

How did covid-19 affect these industries?
The pandemic made Airline industry very volatile, followed by Tech industry and S&P industry.  

What impact did it have on the overall market?
over all market became volatile as pandemic progressed.

What can each industry do next to sustain their business?
 Our advice to these industry is that they need cusion of more cash on hand to survive this pandemic. they can achive that by cutting the divident and cost cutting

Tech industry is doing resonably well how 



Ariline was most volatile in the beganing of the pandemic, followed by tech and lastly S&P became volatile as well.

our analysis shows that it's becoming stable however, it has long way to go.


