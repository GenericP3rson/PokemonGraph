# PokéGraph
Graph of the Pokémon data from the PokéAPI

## Prerequsities

* [pyTigerGraph](https://pypi.org/project/pyTigerGraph/)
* [Requests](https://pypi.org/project/requests/) 

## Quick Set Up

1. [Get Started with TigerGraph Cloud](https://developers.tigergraph.com/quickstart)
2. Run `PokeGraph.ipynb`, replacing it with the appropriate credentials.

## Breakdown

### Data

The data is from the [Pokemon API](https://pokeapi.co/).

### EDA

None, see `PokeGraph.ipynb`

### Scripts

#### Schema

There are two schemas. First, the basic schame:

![Basic Pokemon Graph Schema](https://miro.medium.com/max/4800/1*mlopvqCwJc56z7ax4HB2LA.png)

Next, the extended schema:

![Extended Pokemon Graph Schema](https://miro.medium.com/max/4800/1*Jpp55npG57wYZcd0mt3bOQ.png)

#### Loads

None, see `PokeGraph.ipynb`

#### Query
There are a few queries to grab data for analysis, including:

1. `fiveHeavyPokemon.gsql` —> Grabs the top five heaviest Pokémon.
2. `orderedHeavyPokemon.gsql` —> Grabs all of the Pokémon and orders them by weight. 

## Projects

`K_12_Conference_Notebook.ipynb` —> Full lab of creating a PokéGraph and a dashboard with Plotly

`PokéGSQL.ipynb` —> Lab teaching the basics of GSQL with the TigerGraph Pokémon Graph.

`PokéLinReg.ipynb` —> Lab creating a linear regression using Plotly and the TigerGraph Pokémon Graph.

`PokéComplexSchema.ipynb` –> Lab showing schema change jobs and how to create a more complex schema.

## External Links

* [PokéGraph Part II: Writing Schema Change Jobs for TigerGraph](https://towardsdatascience.com/pok%C3%A9graph-part-ii-writing-schema-change-jobs-for-tigergraph-d6e4d6d4aba0?sk=04581c5ad47e9eb5bc74840a555f2d11)

* [PokéGraph Part IV: Linear Regression with TigerGraph and Plotly Express](https://towardsdatascience.com/pok%C3%A9graph-part-iv-linear-regression-with-tigergraph-and-plotly-express-d9210247d995?sk=48cde025a062c6a7e17c18693a83b097)

* [PokéGraph Part V: Creating a Basic Pokémon Dashboard with TigerGraph, PokéAPI, and Plotly Dash](https://towardsdatascience.com/pok%C3%A9graph-part-v-creating-a-basic-pok%C3%A9mon-dashboard-with-tigergraph-pok%C3%A9api-and-plotly-dash-b86fcf9ed161?sk=55a5f5dbd3655010dc69bbfe021dd94a)
