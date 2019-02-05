# easydb-custom-data-type-getty

This is a plugin for [easyDB 5](http://5.easydb.de/) with Custom Data Type `CustomDataTypeGetty` for references to entities of the [Getty Vocabularys](http://vocab.getty.edu/).

The Plugins uses <http://ws.gbv.de/suggest/getty/> for the autocomplete-suggestions. <http://ws.gbv.de/suggest/getty/> communicates live with getty's sparql-endpoint and works as a proxy.

## configuration

As defined in `CustomDataTypeGetty.config.yml` this datatype can be configured:

### Schema options

* which getty-vocabularys are offered for search (aat, tgn, ulan)

### Mask options

* whether additional informationen is loaded if the mouse hovers a suggestion in the search result

## saved data
* conceptName
    * Preferred label of the linked record
* conceptURI
    * URI to linked record
* _fulltext
    * easydb-fulltext
* _standard
    * easydb-standard

## sources

The source code of this plugin is managed in a git repository at <https://github.com/programmfabrik/easydb-custom-data-type-getty>. Please use [the issue tracker](https://github.com/programmfabrik/easydb-custom-data-type-getty/issues) for bug reports and feature requests!
