# Mapa da Apuração 2026

Interactive map of Brazil showing the 2026 general election results by state, for President, Governor and Senate, in both the first and second rounds. The interface is in Portuguese.

## How to use

Open `index.html` in a browser (internet connection required). It is a single file with nothing to install.

- Data comes straight from the TSE's public result files, and the page refreshes itself every 30 seconds. You can change the interval or turn it off.
- The tabs at the top switch between President, Governor and Senate.
- Click a state to see every candidate and the other races in that state.
- The buttons above the map color the states by candidate, by party, or by the share of voting sections already counted.
- The table at the bottom can be sorted by any column.

## Data

- Results: public result files from the TSE (Brazil's Superior Electoral Court) at [resultados.tse.jus.br](https://resultados.tse.jus.br/oficial/app/index.html). No API key needed.
- State outlines: IBGE (Brazilian Institute of Geography and Statistics) boundary data, embedded in the HTML.
