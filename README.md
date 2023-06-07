# Urban Traffic Simulation for Flood Disruptions

## Project Overview
This project aims to quantitatively evaluate the impact of flooding on urban transportation, particularly focusing on the city of Virginia Beach, VA. By building a sophisticated traffic simulation model in Python, the study reveals the extent to which flooding disrupts the city's transportation network, increases average travel time, and impacts the overall resilience of the roadway system. The model could support decision-making processes for mitigating the effects of flooding on urban transportation.

## Description
During flooding events, the inundation within a city will disrupt road segments and impact transportation adversely. Using the road network data obtained from the [open data portal of VB](https://gis.data.vbgoc.com/) and the inundation maps provided by Loftis et al. (2018), a Python-based simulation model has been developed to mimic the movement of vehicles under both normal and flooding conditions.

The model simulates vehicle movements from 8 AM to 6 PM, covering both morning and evening peak times, and takes into account the influence of other vehicles and the relationship between density and speed.

## Simulation Metrics
The simulation provides several metrics to measure the performance of the road network system during flooding events:

- Average, maximum, minimum, and standard deviation of vehicle travel time
- Number and percentage of cars unable to reach destination within simulation time (10 hours)
- Number and percentage of cars blocked by the inundation

These metrics help in understanding the system's behaviors during flooding and devising optimization insights to increase the roadway system’s overall resilience.

## Installation & Usage
1. Clone the repository: `git clone https://github.com/your_username/your_repo.git`
2. Run the simulation: `python3 main.py`

_Note: Replace the URL and filenames with your actual repository URL and filenames._
