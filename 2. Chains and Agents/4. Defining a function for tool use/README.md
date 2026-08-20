# Defining a function for tool use

## Exercise

You're working for a SaaS (software as a service) company with big goals for rolling out tools to help employees at all levels of the organization to make data-informed decisions. You're creating a PoC for an application that allows customer success managers to interface with company data using natural language to retrieve important customer data.

You've been provided with a pandas DataFrame called `customers` that contains a small sample of customer data. Your first step in this project is to define a Python function to extract information from this table given a customer's name. `pandas` has already been imported as `pd`.

## Instructions

- Define a `retrieve_customer_info()` function that takes a string argument, `name`.
- Filter the `customers` DataFrame to return rows with `"name"` equal to the input argument, `name`.
- Call the function on the customer name, `"Peak Performance Co."`.
