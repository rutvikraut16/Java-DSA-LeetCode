# Best Time to Buy and Sell Stock

## Problem
Given an array of stock prices, determine the maximum profit that can be achieved by buying and selling the stock exactly once.

## Approach
- Traverse the array once.
- Track the minimum price encountered so far.
- Calculate the profit for each day.
- Update the maximum profit whenever a larger profit is found.

## Algorithm
1. Initialize `minPrice` to the largest integer value.
2. Initialize `maxProfit` to 0.
3. Iterate through the prices.
4. Update `minPrice` if a lower price is found.
5. Compute the current profit (`price - minPrice`).
6. Update `maxProfit` if the current profit is greater.
7. Return `maxProfit`.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Concepts Used
- Arrays
- Greedy Algorithm
- One-pass Traversal