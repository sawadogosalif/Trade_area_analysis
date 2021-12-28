# Technical Documentation for Section Trade Area Analysis

# I. Component preparation for trade area analysis

# II. Trade area analysis execution





# I. Component preparation for trade area analysis

## 1. Prepare a hexagonal grid over a selected territory

Form a hexagonal grid - given a diameter for the hexagons to build and a GeoDataFrame on the territory
Overlay the grid on top of the original territory GeoDataFrame


## 2. **Component Preparation for Trade Area Analysis**



- Prep hexagonal grid over a selected territory

- Prep hexagonal-based aggregations over the available external data sources

  - Worldpop data: Population data
  - OSM data: Point of interest data
  - Carto data: Consumer spending data & Socio-demographic data
  - Unacast data Pitney Bowes points of interest data


- Construct a single file with all hexagonal-based data(grid + aggregations)

- Visualize the data

# II. Trade Area Analysis Execution

- 1. Derive density

- 2. Derive urbanicity

- 3. Derive trade area distance

- 4. Form a dataset for further analysis

- 5. Visualize the data
