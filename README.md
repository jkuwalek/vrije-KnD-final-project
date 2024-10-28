# How to run

This project uses [pixi](https://pixi.sh/) to manage decencies.

1. Install [pixi](https://pixi.sh/)
2. Open the src/final_result/final pipeline.ipynb
3. Select the pixi environment as the kernel
4. Run the notebook

# Structure

### src/steps

This folder contains some draft notebook that we used while prototyping the final one. The notebooks in that directory are not expected to work.

### src/final_result

This folder contains our final project. The final pipeline is our main and only data processing pipeline. This file loads the csv data, queries the sparql endpoint, runs the reasoner, and visualizes and analyzes the covid19 spread data.
