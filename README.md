# Japanese Db Maker

Japanese language resources database maker from various open source materials.

(This module is still under initial development)

# Usage
1. Download required materials
    - Download `JMdict_e.gz` from http://www.edrdg.org/jmdict/edict_doc.html.
    - Download `JMnedict.xml.gz` from https://www.edrdg.org/enamdict/enamdict_doc.html.

1. Extract all the files and put it in a folder (e.g. `sourceFolder`)
    ```
    myJpProject/
    ├── sourceFolder/
    │   ├── JMdict_e
    │   └── JMnedict.xml
    └── destinationFolder/

    ```
1. Open `myJpProject` folder in terminal.

1. Run following commands

    ```sh
    npm install japanese-db-maker -g
    japanese-db-maker sqlite -s ./sourceFolder -d ./destinationFolder
    ```

## Development

### Testing
```sh
npm link .
npm test
```

## Authors

* **Ezzat Chamudi** - [ezhmd](https://github.com/ezhmd)

See also the list of [contributors](https://github.com/ezhmd/japanese-db-maker/graphs/contributors) who participated in this project.

## License

Code and documentation copyright 2019 the [Japanese Db Maker Project Authors](https://github.com/ezhmd/japanese-db-maker/graphs/contributors). 

Japanese Db Maker code is licensed under [MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/). Images, logos, docs, and articles in this Japanese Db Maker project are released under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode).

Libraries, dependencies, and tools used in this project are tied with their own licenses respectively.

