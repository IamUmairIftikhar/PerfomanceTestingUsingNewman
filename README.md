# Running multiple Postman Collection in parallel

A known limitation of the Postman Collection Runner is that it can only execute collection in a consecutive way. 

## Export your collection and the environment variables

![Export collection](docs/export-collection.png)

And save the files in a `postman/` directory. 

## Create the new npm project

Simply run `npm init -y` and install the 3 dependencies: `npm i async newman path`

## The script !

Run the script using `npm start`command

![running results](docs/run-result.png)
