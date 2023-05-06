# Airline Revenue Management

Project as part of Optimization II Coursework

# Description

This project aims to help an airline company maximize its revenue through dynamic pricing and overbooking strategies.

The program uses dynamic programming to calculate the optimal prices for first-class and coach tickets on a daily basis, based on the company's overbooking policy and expected profit.

Two different strategies are explored: a hard cutoff point for the number of overbooked tickets, and a dynamic overbooking policy that allows the airline to stop selling tickets to optimize the number of overbooked passengers.

The program also takes into account the cost of upgrading coach customers to first class and the cost of offering vouchers to overbooked customers.

The project provides four pricing decisions:

    Low price Coach, Low price First
    High price Coach, Low price First
    Low price Coach, High price First
    High price Coach, High price First

The program also considers nine daily situations:

    Sold Low Coach, Sold Low First
    Sold High Coach, Sold Low First
    Sold Low Coach, Sold High First
    Sold High Coach, Sold High First
    Not Sold Coach, Sold Low First
    Not Sold Coach, Sold High First
    Sold Low Coach, Not Sold First
    Sold High Coach, Not Sold First
    Not Sold Coach, Not Sold First

The first strategy determines the maximum expected profit by setting the number of allowed overbooked tickets between 5 to 15. The second strategy allows the program to find the optimal number of overbooked passengers and the optimal time to stop selling tickets to maximize profits.

The program uses a discount rate of 17% per year, and assumes that coach customers have a 95% likelihood of showing up for their flight and first-class customers have a 97% likelihood of showing up.

This program can assist an airline company in making data-driven decisions to increase its revenue while optimizing its overbooking policy.
