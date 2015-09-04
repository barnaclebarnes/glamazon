# GLAMAZON

{ **G**alleries, **L**ibraries, **A**rchives, **M**useums, **A**quariums, **Z**oos, **O**bservatories, **N**ature Reserves}

This dataset pulls together all of the museums and cultural organisations around the world. Currently 43249 organisations are in the dataset.

## Data Format

The `organisations` folder contains a series of folders with the first 3 numbers of the ID. Under that is a file for each organisation. For example:

```
organisations\123\123456.json
organisations\123\123457.json
```

The records themselves are [Schema.org](http://schema.org/Place) Place records.

The following fields are locallised:

* name
* openingHours
* offers

These will use the `@value` and `@language` construct from `JSON-LD`:
```
"openingHours": [
    {
        "@value": "Mercoledì - domenica 10-17 settembre chiuso giugno-agosto e giorni di funzionamento giorno di Natale per l'estate 2014-15 sarà presto confermati", 
        "@language": "it"
    }, 
    {
        "@value": "Среда - воскресенье, сентября 10: 00 утра - 5:00 pm 10.00 - 17.00 закрыт с июня по август и Рождество операционной дней лета 2014-15 будет подтверждено скоро", 
        "@language": "ru"
    }
]
```

## Contributing

Feel free to fork the repo and create a pull request for any updates. Just let me know where the data was sourced.

## License

The data is licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license unless otherwise stated. The data included for now are only facts unless the source data was licensed under a permissive license. Further information such as descriptions will be added over time where data can be obtained (via Wikipedia, etc.)