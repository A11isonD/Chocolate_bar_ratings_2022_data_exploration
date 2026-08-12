
![Logo](https://www.publicdomainpictures.net/pictures/540000/velka/stacked-chocolate-bars-1694790002vvc.jpg)


# Chocolate Bar and Coffee Analytics

This project explores rating trends for various chocolate bars based on their ingredients, percent cocoa, flavor profiles, bean origin, and manufacturer. Since there is some overlap in growing regions for coffee and cocoa, I also included an analysis of a coffee ratings dataset, as well as an exploration of countries that produce both. The project overall demonstrates the processes of data cleaning, exploratory data analysis, and visualization in Python, and database creation and queries with SQL.   

Some of the main questions explored are:    
1. Which countries grow the most cocoa and which ones produce the most chocolate?    
2. Does cocoa percentage influence the chocolate bar rating?    
3. Is there a relationship between cocoa percentage and the country of origin?


## Data Sources

Both datasets were obtained from Kaggle.com.     
https://www.kaggle.com/datasets/nyagami/chocolate-bar-ratings-2022    
https://www.kaggle.com/datasets/schmoyote/coffee-reviews-dataset?select=simplified_coffee.csv


## AI Statement

Copilot in Microsoft Edge returns AI-generated content (in addition to traditional search results), which was used to aid in learning and problem-solving. Claude AI was also used during the last several days of project completion. AI served as a starting point to get an overview of an issue before delving into the traditional search results, which is where I obtained the majority of my information.  AI also helped to clarify complex concepts, assist in logical thought and problem solving, and identify and explain errors. Any results obtained through AI were checked against existing information in class content and on trusted websites.     


## Usage

1. Clone this repository.   

2. Set up your virtual environment       
    a. Create the virtual environment    
    ```    
    # windows    
    python -m venv venv    
    # mac / linux    
    python3 -m venv venv
    ```    
    b. Activate the virtual environment    
    ```    
    # windows    
    source venv/Scripts/activate        
    # mac / linux    
    source venv/bin/activate    
    ```    
    c. You will know it was successful when you see (venv) at the start of your terminal prompt.    

3. Install the required Python packages:              
    ```
    pip install -r requirements.txt    
    ```            

4. Open and run the following Jupyter notebook files in this order:     
    a.  ../Notebooks/chocolate_bar_ratings_exploration.ipynb    
    b.  ../Notebooks/chocolate_bar_ratings_plots.ipynb    
    c.  ../Notebooks/simplified_coffee_eda.ipynb    
    d.  ../Notebooks/chocolate_coffee_ratings.ipynb         

5. When opening the first notebook in step 4, click the kernel picker (top right of the notebook) and choose venv as the kernel - it will be under Python Environments.    

6. Deactivate the virtual environment when done working.    
```
# windows / mac /linux    
deactivate    
```
 


## Findings, Observations, and Conclusions    

1. Most of the chocolate bars with 60-80% cocoa had ratings between 2.5 - 4.0.    
2. Chocolate bar ratings were not evenly distributed; more bars were rated between 3.0-3.5 than any other value. 
3. Venezuela and Peru were the top two cocoa producing countries.
4. Ecuador was in the top 10 countries for both cocoa production and chocolate manufacturing.
5. The United States was the largest producer of the chocolate bars included in this review.
6. There was no relationship between the cocoa percentage and country of origin.
  

## Authors

[Allison Dobbs, Data Analysis Student at Code:You](https://github.com/A11isonD/Chocolate_bar_ratings_2022_data_exploration)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Acknowledgements

 - [Code:You](https://codelouisville.org/)
 - [readme.so](www.readme.so)
 - [Lucidchart](www.lucidchart.com)
 - [smartdraw](www.smartdraw.com)
 - [TOP HAT](https://tophat.com)
 
