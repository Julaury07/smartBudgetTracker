# smartBudgetTracker
iOS Budget Tracking App Project

# Smart Budget Tracker

## Table of Contents

1. Overview
2. Product Spec
3. Wireframes
4. Schema


# Overview

## Description

Smart Budget Tracker is a mobile app that allows users to track their income and expenses, categorize transactions, and monitor their financial activity. Users can also attach receipt photos to each transaction for better organization.


## App Evaluation

Category: Finance / Productivity

Mobile: Yes  designed specifically for mobile devices, using features like photo library (receipts) and push notifications

Story: The app helps users take control of their finances by making it easy to track spending and understand where their money goes

Market: Students, young adults, families, and anyone who wants to manage their budget

Habit: Users can log expenses daily or multiple times per week, encouraging consistent use

Scope: Narrow to medium  focused on core budgeting features with optional enhancements



# Product Spec

## 1. User Stories (Required and Optional)

### Required Must-have Stories

* User can add a transaction (income or expense)
* User can enter amount, category, and title
* User can view a list of transactions
* User can see total balance
* User can categorize transactions



### Optional Nice-to-have Stories

* User can attach a receipt photo
* User can receive reminders to log spending
* User can view spending by category
* User can delete a transaction



## 2. Screen Archetypes

### Home Screen

* User can view total balance
* User can view recent transactions
* User can navigate to add transaction


### Add Transaction Screen

* User can input transaction details
* User can attach a receipt photo
* User can save a transaction



### History Screen

* User can view all transactions
* User can see category and amount
* User can view receipt image (optional)



## 3. Navigation

### Tab Navigation (Tab to Screen)

* Home
* Add Transaction
* History


### Flow Navigation (Screen to Screen)

Home Screen
Leads to Add Transaction Screen

Add Transaction Screen
>Save > Returns to Home Screen

Home Screen
>Leads to History Screen

History Screen
 >Back to Home Screen



# Wireframes

(Add your hand-drawn or digital wireframe images here)
<img width="4720" height="3280" alt="IMG_1005" src="https://github.com/user-attachments/assets/9f0fecf0-598a-43c0-901d-ac65d487284d" />



# Schema

## Models

### Transaction

[PROPERTY]  [TYPE]  [DESCRIPTION]

id        | UUID   | Unique identifier 
name      | String | Transaction title 
amount    | Souble | Transation amount 
category  | String | Expense caategory 
date      | Date   | Date of tansaction 
image data | Data  | Recepipt image 


## Networking

This app will primarily use a local database (Core Data), so no external API is required for MVP.

(Optional future networking)

* Sync data to cloud storage
* Backup user transactions
