# PeopleWeave_Project

## Overview
The PeopleWeave Project analyzes relationships between millions of CS researchers to create an algorithm to match researchers with similar interests. 

## Setup
1. Clone repo + install dependencies
      - Clone this repository onto local drive
      - Install dependencies:
         ```
         pip install -r requirements.txt
         ```
2. Download dataset (view link under "Resources") and save as dblp.xml

## Usage
### parse_xml.ipynb: 
  - extracts data from [dblp](https://dblp.org/) dataset containing information about 6+ million CS research papers. Reads the data into a social graph relating researchers.

### graph_algorithms.ipynb: 
  - various graph algorithms to answer questions about researcher relationships (ex: "Are there certain groups of researchers that are 'cliquish' and only work with each other?")

## Resources:
Download the dblp dataset by following the instructions [here](https://dblp.org/faq/1474681.html).
