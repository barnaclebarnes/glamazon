# GLAMAZON

{ __G__aleries, __L__ibraries, __A__rchives, __M__useums, __A__quariums, __Z__oos, __O__r, __N__ature Reserves}

This dataset pulls together all of the museums and cultural organisations around the world. Currently 43249 organisations are in the dataset.

## Data Format

The `organisations` folder contains a series of folders with the first 3 numbers of the ID. Under that is a folder for each organisation and within that a series of files for each organisation that have been localised. For example:

`organisations\123\123456\123456-en.json`
`organisations\123\123456\123456-it.json`

The records themselves are [Schema.org](http://schema.org/Place) Place records.

## Contributing

Feel free to fork the repo and create a pull request for any updates. Just let me know where the data was sourced.

## License

The data is licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license unless otherwise stated. The data included for now are only facts unless the source data was licensed under a permissive license. Further information such as descriptions will be added over time where data can be obtained (via Wikipedia, etc.)

