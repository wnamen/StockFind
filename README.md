# StockFind

The objective is to build a functional StockFind app using the official Barchart Free API.

## Project Overview

This app should contain at least 2 pages, Home and Stock. The Home page should serve as a generic landing page with 
the ability to search for a ticker. Upon a successful search, the user should be redirected to the
stock page where some basic, real-time data is displayed.

Required Tech:

1. React
2. Redux
3. React-Router
5. Axios or Request
6. Create-React-App
3. Barchart Free API
7. AWS

## Step 1: Initial Architecture

Use create-react-app to quickly deploy a new react app.

## Step 2: Home Page

![Alt text](./home-page.png?raw=true "Home Page")

Required Features:
1. Home page
    1. Hero title
    2. Centered search bar with button


## Step 3: Stock Page

![Alt text](./stock-page.png?raw=true "Home Page")

Required Features:
1. Stock page
    1. Navbar
        1. Left app title with breadcrumbs. Clicking on the title should return you home
        2. Right search bar with button
    2. Centered container
        1. Left column should contain the ticker, exchange, and a visual icon showing trend
        2. Right column should contain last price, change, and percent change with their respective results to the right

## Step 4: Wire Up the Stock Data

Use the following link to documentation on how to access Barchart's Free API:

https://www.barchart.com/ondemand/free-market-data-api

Use redux to handle the API call and pass the data to the UI.

## Step 5: Build for Production and Deploy

Now that the app is complete, build a production version of the app and deploy it using AWS. You can use an Elastic Beanstalk or S3 Web Hosting.

## Step 6: Submission

Send us a link to your newly deployed app and github repo.
