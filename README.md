# Jiayang Sun PS1

## Project Title
Ticketing Rules, Speculation, and Genuine Audience Access in Digital Markets

## Course
COMSCI/ECON 206 Computational Microeconomics  
Autumn 2026 Session 1  
Instructor: Luyao Zhang

## Research Question
This project compares two digital ticketing rules:

1. Refundable but non-transferable tickets
2. Transferable but non-refundable tickets

The goal is to examine how these rules affect speculative resale and genuine audience access.

## Computational Model
The simulation includes:

- Ticket supply
- Genuine audience demand
- Share of speculative resellers
- Refund behavior
- Resale success
- Ticketing rule

The main outcome is the genuine audience access rate.

## Notebook
The main notebook is:

`ticketing_simulation.ipynb`

It can be opened and run in Google Colab.

## How to Run
1. Open `ticketing_simulation.ipynb`.
2. Open the notebook in Google Colab.
3. Run all cells from top to bottom.
4. Change parameters such as `reseller_share` to explore alternative scenarios.

## Dependencies
The notebook uses:

- Python
- pandas
- matplotlib
- random

No API key or GPU is required.

## Current Results
Using synthetic assumptions with:

- 100 tickets
- 140 genuine consumers
- reseller share from 0% to 50%
- refund rate = 0.80
- resale success rate = 0.70

the simulation shows that genuine audience access decreases as the reseller share increases.

Under the current synthetic assumptions, the refundable but non-transferable rule produces a higher genuine audience access rate than the transferable but non-refundable rule.

At a reseller share of 50%:

- Refundable but non-transferable: approximately 63.6%
- Transferable but non-refundable: approximately 60.0%

These are simulated results, not empirical findings.

## Limitations
The refund rate and resale success rate are assumed parameters rather than estimates from real-world data.

The model is designed as a transparent baseline for comparing ticketing rules, not as a complete representation of actual ticket markets.

## Author
Jiayang Sun  
Duke Kunshan University  
js1172@duke.edu
