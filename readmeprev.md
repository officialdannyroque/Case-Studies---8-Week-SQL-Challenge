# 8 Week SQL Challenge 🚀
# Case Study #1: Danny's Diner

This repository showcases my personal solutions to the [8 Week SQL Challenge](https://8weeksqlchallenge.com/) curated by Danny Ma.
![Danny's Diner ERD](https://github.com/user-attachments/assets/c1e2b31b-fbdb-4ccb-873f-2ee98b77743f) <!-- replace with your actual ERD image path if using -->

---

## 📑 Table of Contents
## 📚 Table of Contents

- [Introduction](#introduction)
- [Case Study Solutions](#case-study-solutions)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Acknowledgments / References](#acknowledgments--references)
- [Problem Statement](#-problem-statement)
- [Datasets Used](#-datasets-used)
- [Entity Relationship Diagram](#entity-relationship-diagram)
- [Case Study Questions + Bonus](#case-study-questions--bonus)
- [Relevant Links](#-relevant-links)
- [Contributing](#contributing)
- [Support](#Support)
- [Support](#support)

---

## Introduction

The **8 Week SQL Challenge** is a collection of hands-on case studies designed to sharpen your SQL proficiency. Each case mirrors a realistic business scenario, and you'll be challenged to extract insights using structured queries.
Danny is a die-hard fan of Japanese cuisine and in early 2021 decided to launch a cozy restaurant offering his three favorite dishes: **sushi**, **curry**, and **ramen**.

This repo contains my answers, explanations, and any helpful resources I used throughout the challenge.
Although the food has heart, the business needs help, Danny has gathered some basic transactional data but lacks the skills to extract meaningful insights. That’s where this case study begins.

As part of my data analyst portfolio, this project demonstrates how SQL can be used to support business decisions in the restaurant industry.

---

## 🎯 Problem Statement

Danny is interested in understanding customer behavior to improve operations and customer retention. Specifically, he wants to uncover:

- How often customers visit
- What they order most frequently
- How much they’ve spent
- How effective the current loyalty program has been

With these insights, he hopes to enhance the dining experience and decide whether to expand his loyalty rewards system.

---

## Case Study Solutions
## 🧾 Datasets Used

Each case study has its own folder containing the solution:
Three key tables form the foundation of this case study:

- **#1 – Danny's Diner**
- **#2 – Pizza Runner**
- **#3 – Foodie-Fi**
- **#4 – Data Bank**
- **#5 – Data Mart**
- **#6 – Clique Bait**
- **#7 – Balanced Tree Clothing Co**
- **#8 – Fresh Segments**
- `sales`: Records each customer's order history including `customer_id`, `order_date`, and `product_id`
- `menu`: Maps each `product_id` to its `product_name` and `price`
- `members`: Tracks when each customer joined the loyalty program via `join_date`

---

## Technologies Used
## Entity Relationship Diagram

- **SQL** – All challenges are solved using SQL
- **PostgreSQL v15** – My RDBMS of choice for running queries
![Entity Relationship Diagram](https://github.com/user-attachments/assets/c621b967-ad68-43a3-a99b-d77699a195ae)  
*Diagram created via [dbdiagram.io](https://dbdiagram.io)*

---

## How to Use
## Case Study Questions + Bonus

1. What is the total amount each customer spent at the restaurant?  
2. How many days has each customer visited the restaurant?  
3. What was the first item from the menu purchased by each customer?  
4. What is the most purchased item on the menu and how many times was it purchased by all customers?  
5. Which item was the most popular for each customer?  
6. Which item was purchased first by the customer after they became a member?  
7. Which item was purchased just before the customer became a member?  
8. What is the total items and amount spent for each member before they became a member?  
9. If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?  
10. In the first week after a customer joins (including join date), they earn 2x points on all items, how many points do customers A and B have at the end of January?

1. Clone this repository to your local environment
2. Ensure PostgreSQL or your preferred SQL tool is installed
3. Navigate into any case study folder you're interested in
4. Read the Markdown files for explanations and query links (e.g. DB Fiddle)
5. (Optional) Execute the queries in your own SQL client or DB browser
### Bonus Questions

Each `.md` file includes a direct DB Fiddle link so you can run queries instantly without setting up anything locally.
- Join All The Things  
- Rank All The Things

---

## Acknowledgments / References
## 🔗 Relevant Links

- Big thanks to **Danny Ma** for crafting this incredible learning challenge
- Visit the official [8 Week SQL Challenge website](https://8weeksqlchallenge.com/)
- Also inspired by:
  - [Katie Huang on GitHub](https://github.com/katiehuangx)
- [Entity Relationship Diagram – dbdiagram.io](https://dbdiagram.io/d/Dannys-Diner-608d07e4b29a09603d12edbd?utm_source=dbdiagram_embed&utm_medium=bottom_open)
- [DB Fiddle SQL Schema & Playground](https://www.db-fiddle.com)

---

## Contributing

I’m always open to suggestions and collaboration!  
If you spot bugs, want to contribute improvements, or have a creative spin—feel free to open a new issue or submit a pull request.
Contributions are always welcome!

You can also connect with me on [LinkedIn](https://www.linkedin.com/in/daroque/) or open a discussion in this repo.

Let’s keep learning together!
If you’d like to suggest improvements or fix something, feel free to fork the repo and open a pull request.

---

## Support

If you find this repo helpful or inspiring, a ⭐ would mean a lot!
Have questions or suggestions?  
You can reach me via [LinkedIn](https://linkedin.com/in/YOUR-NAME-HERE) or open an issue in this repository.

If this project helped you, inspired you, or gave you ideas of your own, please consider giving it a ⭐!
