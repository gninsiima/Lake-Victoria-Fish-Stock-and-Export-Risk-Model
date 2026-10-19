### Lake Victoria Fish Stock and Export Risk Model
# Lake Victoria Fish Stock and Export Risk Model

A Python-based analytical tool designed to model fish stock dynamics, evaluate sustainable harvest levels, and assess export risks for fisheries around Lake Victoria.

## Project Overview
This repository contains simulation models, mathematical formulations, and analytical scripts to monitor ecological sustainability and model economic/export risk metrics under varying catch scenarios.

## Repository Structure
- `src/` - Core simulation scripts, ecological modeling logic, and risk assessment modules.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/gninsiima/Lake-Victoria-Fish-Stock-and-Export-Risk-Model.git](https://github.com/gninsiima/Lake-Victoria-Fish-Stock-and-Export-Risk-Model.git)
   #### Findings
   The biological and economic simulation of Lake Victoria’s fishery dynamics underscores the critical tension between short-term commercial export revenue and long-term ecological sustainability. The Schaefer surplus production model confirms that when fishing effort exceeds the Maximum Sustainable Yield threshold, fish biomass declines rapidly, leading to diminishing marginal returns and an escalating risk of stock collapse. While aggressive harvesting maximizes immediate export earnings of Nile perch, it creates severe vulnerability for local processing plants and fishing communities facing subsequent stock crashes. Furthermore, stochastic export risk simulations highlight that external market price volatility compounds biological pressures; when international prices dip, fishers often increase catch volumes to maintain baseline income, accelerating overfishing. These findings demonstrate that effective fisheries management cannot rely solely on open-access market forces; it requires legally enforced quotas, seasonal gear restrictions, and cooperative regional governance between Uganda, Kenya, and Tanzania to protect the lake's ecological integrity.
   #### Limitations
   Despite providing valuable macro-level insights, the model contains structural simplifications. First, the Schaefer surplus production model treats the fishery as a single-species aggregate, ignoring complex multi-species trophic interactions—such as predator-prey dynamics between Nile perch, haplochromines, and Nile tilapia. Second, the environmental carrying capacity ($K$) is treated as a static parameter, failing to account for exogenous shocks such as eutrophication, water temperature changes, and industrial pollution altering the lake's biological productivity. Finally, the export risk model assumes stationary price distributions, omitting geopolitical trade barriers or sudden regulatory shifts in European export markets. Future iterations should incorporate age-structured population models and environmental covariate tracking.
