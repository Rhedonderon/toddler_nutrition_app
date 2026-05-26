# 🍼 Toddler Nutrition Data Product Concept
## Introduction
This repository contains an end-to-end data analytics and product validation workflow for a mock toddler nutrition tracking application. Managing a child's diet during the transition to solid foods often introduces significant nutritional anxiety for parents, particularly regarding micronutrient thresholds (such as iron and zinc).

While this is a conceptual portfolio project engineered to demonstrate my technical upskilling, every phase of the pipeline—from primary data collection to data architecture—is executed using real-world industry methodologies. 

## Core Capabilities Demonstrated:
### Primary Market Research:
Designing and deploying a 10-question user friction survey to gather raw consumer insights.

### Data Engineering & Integration:
Using Python (pandas) to clean, structure, and join primary survey data with complex secondary datasets (the USDA FoodData Central database).

### System Design Thinking:
Architecting a relational data schema built around user-centric app features like bioavailability tracking and multi-caregiver syncing.

## 📋 Phase 1: Data Collection & Requirements Gathering

To validate the features of this toddler nutrition product concept and understand real-world user friction, I conducted primary market research using a targeted, anonymous consumer survey. 

* **Target Audience:** Parents and primary caregivers of toddlers aged 1 to 3.
* **Objective:** Identify the core pain points regarding toddler meal prep, nutritional tracking anxiety, and desired application features.
* **Survey Design:** A 10-question instrument tracking demographics, mealtime frequencies, logging friction, and feature prioritization.

### Project Artifacts
* **Blank Form User Experience:** You can view the live layout and question logic of the active survey here: [https://docs.google.com/forms/d/e/1FAIpQLScmcMNsLLhEIGq5YWMWbiB1Dy8RXyE1Cs9bwoNvZiRwkt7oDg/viewform?usp=preview]
* **Raw Survey Dataset:** The completed, anonymous response data is stored as a flat file in this repository at `data/raw_survey_responses.csv` *(Note: This dataset will be populated upon completion of the data collection phase).*
