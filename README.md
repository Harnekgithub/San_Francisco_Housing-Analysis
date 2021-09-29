# San_Francisco_Housing-Analysis

##Real Estate Investment Dashboard
In this project goal was to create a dashboard to provide charts, maps, and interactive visualizations to investors to explore the data and determine if they want to invest in rental properties or not. Target market was San Francisco.

Getting Started
    Goals
    ##Complete a notebook of rental analysis
        *Load data from the CSV files
        
            *Load mapbox api keys for the use of mapbox libraries

            *Generated visualizations for the average housing units per year

            *Calculated and Ploted the average sale price per square foot and average gross rent

            *Plot using hvplot create two interactive visulizations of average prices and average gross rents with a dropdown selector for the neighborhood

            *Plot the data for the top 10 expensive neighborhoods using hvplot

            *Using hvplot create side-by-side comparison visualization of average price per square foot and average monthly gross rent by year for each neighborhood using a drop down.

            *Read the neighborhood location and create a new data frame combine location data with mean values of rental and sale data

            *Used the new data set to visualize the neighborhoods on a map using mapbox and show all the mean info on the map.

            *Generated the parallel categories and coordinate visualizations to for cost rent analysis for the top 10 most expensive neighborhoods.

            *Created a sunburst chart to help with costs analysis of most expensive neighborhoods in San Francisco per year
        
    
    
    ## Create a dashboard of interactive visualizations to explore the market data

        Once the Rental Analysis was done then all sections were port to the dashboard to create individual functions that were called to create panels library and further code for 10 most expensive neighborhoods was put in a seperate function to be used in multiple other functions for clean reuse of the code and easy of future changes to logic or rules.
        
    #Generating a Dashboard
        Now that all code was in place to generate interactive dashboard for all of the visualizations panel.servable() command was fired to test it out in Jupyter Notebook.
        Finally it was deployed to Bokeh server on a localhost.
        