## Table of Contents
1. [Objective](#objective)
2. [Requirements](#requirements)
3. [Use](#use)

## Objective

The objective of this project is to develop a working solution to the [Traveling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem) using the Ant Swarm Optimization algorithm.

In addition to implementing a solution, I also wanted to develop a deep understanding of the ASO algorithm – its methods, use-cases, advantages, and disadvantages.

One last personal goal of mine is to include some visualization of the data/results acquired from runs of the solution. 

_Notes_:
- This project will be using slightly modified source code from [another project of mine solving the TSP using a genetic algorithm](https://github.com/KayDVC/Travelling-Salesman-Problem). Any modifications will be discussed.

## Requirements

The project has the following baseline requirements derived from the problem description:
1. The solution must generate a list of cities.
2. The solution must generate a list of distances between each city and all others.
3. The solution must find the shortest path between all cities.
    * All cities, except the origin city, must be visited exactly once.
    * The solution must start and end at the origin city.
       
In addition to the baseline requirements, the following requirements assist in creating a good testing environment for the genetic algorithm :
* At least 25 cities must be generated.
* All cities must reside within a 200\*200 unit plane. The units can be interpreted as kilometers.
* All cities must be generated at random coordinates (overlap possible, but highly improbable).

Lastly, each design choice is explained within the context of the problem. 

"If you can't explain it to a six-year-old, then you don't understand it yourself" (Einstein).

## Use
The project requires [Jupyter Notebook](https://jupyter.org/) to *modify*.

Python Version: `<= 3.11`

See `requirements.txt` for full requirement list.

If used as "inspiration," please link back to this repo.

Thanks,

\- Kay

