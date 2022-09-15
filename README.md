# TITLE

## Project Summarry
/ describe shortly the goal of this project /

## Contents
[1. Introduction](#1-introduction) 
      
   - [Problem Background and Research Motivation](#11-problem-background-and-research-motivation)
   
   - [Problem Statement and Research Questions](#12-problem-statement-and-research-questions)
   
   - [Conceptual Model](#13-conceptual-model)

[2. Methodology](#2-methodology)
 
   - [Data](#21-data)

   - [Research Method](#22-research-method)

   - [Analysis](#23-analysis)

[3. Results and Interpretation](#3-results-and-interpretation)

[4. Repository Overview](#4-repository-overview)
   
   - [Repository Contents](#41-repository-contents)
   
   - [Repository Structure](#42-repository-structure)

[5. Instructions to Run the Project](#5-instructions-to-run-the-project)
   - [Software Setup](#51-software-setup)
   - [Run the Code](#52-run-the-code)

[About Us](#about-us)

[References](#references)


## 1. Introduction
### 1.1 Problem Background and Research Motivation
The start of the academic year for university students can be a stressful period for many reasons, finding housing is one of them. In this current research we aim to investigate how the AirBnb market is affected in different Western-European cities by the start of the academic year. The Berlin Spectator recently described the ease with which students can find housing in Berlin is largely base on luck. In a popular Belgian student city, after publishing an advertisement for student rooms, housing agents needed to ignore students' phone calls, as distress among them for rooms and studios was increasing. NL Times published an article in which University of Amsterdam is warninh students not to come to the Netherlands without housing. It is obvious that in all these three countries finding student accomodation is a serious problem for newcomers. However, it is less obvious how this crisis affects the AirBnb market as a possible alternative for students looking for (temporary) accomodation. To what extent does the situation differ across cities in different countries? As a result of our research, we hope to answer the following main research question and sub-questions.

### 1.2 Problem Statement and Research Questions

*To what extent does the start of the Academic year affect the AirBnB market in popular student cities in Europe?*
- Do the the Air BnB prices change? Do they increase or decrease?
- Does the minimum number of nights per which an accomodation change? If so, does it increase or decrease?
- Is there a difference in price change between professional hosts and ordinary ones?

Cities of interest to use (all large student cities with Universities):
- The Netherlands (Amsterdam, Rotterdam), Germany (Berlin, Munich), Denmark (Copenhagen), Belgium (Brussels, Ghent, Antwerp), Austria (Vienna) 


### 1.3 Conceptual model
/ visualize the conceptual model (e.g. with draw.io) and add the file here /

## 2. Methodology
### 2.1 Data
    - Data Sources
    - Overview of the Variables
        We have access to data going back 12 months.

        Variables that are important for our research are:
        - id                              = Airbnb's unique identifier for the listing 
        - host_location                   = The host's self reported location
        - host_about                      = Description about the host
        - host_is_superhost               = boolean [t=true; f=false]
        - neighbourhood_cleansed          = The neighbourhood as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital                                               shapefiles.
        - property_type                   = Self selected property type. Hotels and Bed and Breakfasts are described as such by their hosts in this field
        - price                           = daily price in local currency
        - availability_30                 = avaliability_x. The availability of the listing x days in the future as determined by the calendar. Note a listing may not be                                           available because it has been booked by a guest or blocked by the host.
        - number_of_reviews               = The number of reviews the listing has
        - number_of_reviews_l30d          = The number of reviews the listing has (in the last 30 days)
        - calculated_host_listings_count  = The number of listings the host has in the current scrape, in the city/region geography.

### 2.2 Research Method
/ explain the research method /

### 2.3 Analysis
/ explain the analysis /

## 3. Results and Interpretation
/ add text /

## 4. Repository Overview
### 4.1 Repository Contents
### 4.2 Repository Structure
/ provide an overview of the directory structure and files (use the tree command) /

## 5. Instructions to Run the Project
### 5.1 Software Setup
### 5.2 Run the Code
/ add clear instructions /

## About Us
/ add the names and roles of all contributors /

## References
/ add all references in APA style /

