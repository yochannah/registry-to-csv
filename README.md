# registry-to-csv
node script to convert registry json to csv, for excel / google sheets goodness. Assumes you have node and npm installed

To run:

1. clone this repo
2. npm install dependencies (jsontocsv package)
3. go to the registry and copy all the json here: http://registry.intermine.org/service/instances
4. open index.js and replace the old registry info with the new stuff you just copied.
5. save
6. on the command line, run `node index.js > somefilenamehere.csv`

if you want to edit what fields are output, edit this line: 
