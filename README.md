# wiki-mcc-mnc-scrapper
This is a ruby script that will fetch the full list of Mobile Country Code (MCC)
and Mobile Network Code (MNC) for all the Mobile Network Operators (MNO) of the
world from the wiki page entry https://en.wikipedia.org/wiki/Mobile_country_code
and output a CSV file with the given format:

```
Country,CountryISO,MCC,MNC,Brand,Operator,Status
```

So you can later work with this information.

# Running it
Just fetch the code and then:
```sh
./wiki-mcc-mnc-scrapper
```

## Contributing
To contribute:
 * Make sure you open a **concise** and **short** pull request.
 * If your code is accepted, it will belong to PortaText and will be published
 under the Apache2 License.

# License
The source code is released under Apache 2 License.

Check [LICENSE](https://github.com/marcelog/wiki-mcc-mnc-scrapper/blob/master/LICENSE) file for more information.
