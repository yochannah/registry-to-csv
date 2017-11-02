# registry-to-csv
node script to convert registry json to csv, for excel / google sheets goodness. Assumes you have node and npm installed

## To run:

1. clone this repo
4. on the command line, `cd` into the newly cloned folder, e.g. `cd registry-to-csv`
2. on the command line, run `npm install` to install dependencies (jsontocsv package)
3. go to the registry and copy all the json here: http://registry.intermine.org/service/instances
4. open index.js and replace the old registry info with the new stuff you just copied.
5. save
6. on the command line, run `node index.js > somefilenamehere.csv`

voila! `somefilenamehere.csv` will now have the data you're looking for

## Choosing which fields to output

if you want to edit what fields are output, edit the `fields` array on this line: https://github.com/yochannah/registry-to-csv/blob/9e432f1708f999f42cd66fd02b834b77a4f01fa5/index.js#L1136
