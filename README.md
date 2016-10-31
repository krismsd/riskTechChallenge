# Bet Risk Tech Challenge

App for analysing client risk from betting data. Built using [Polymer](https://www.polymer-project.org).

## Running

To run (assuming you have NodeJS + Bower installed):

```
npm install -g polymer-cli # Install polymer cli
polymer serve # Serve the site
```

The site should now be running at http://localhost:8080/


## Running Tests

```
$ polymer test
```

## Update CSV data

The `unsettled.csv` and `settled.csv` files are in `src/risk-app/`. These may be
replaced to update the betting data.
