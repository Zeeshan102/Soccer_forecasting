# 2018 FIFA World Cup Simulator
This project simulates the group stage matches of the 2018 FIFA World Cup using a Poisson distribution to generate match scores. It also calculates the group standings based on the simulated outcomes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [License](#license)
- [Contact](#contact)

## Overview

The simulation takes a list of qualified teams with their draw positions and simulates the round-robin matches in each group. For each match, the number of goals for each team is generated using a Poisson distribution (with a configurable mean, defaulting to 1.5). After all matches have been simulated, the project calculates group standings including points, goals for, goals against, and goal difference.

## Features

- **Match Simulation:** Generates realistic match outcomes using a Poisson process.
- **Group Standings:** Computes points, goal difference, and other metrics for each group.
- **Modular Codebase:** Organized into functions for easy maintenance and further development.
- **Configurable Parameters:** Easily adjust simulation parameters such as the Poisson lambda value.

## Prerequisites

- Python 3.6 or higher
- Required Python packages:
  - `pandas`
  - `numpy`

You can install the required packages using pip:

```bash
pip install pandas numpy
