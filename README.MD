[TODO] : Add more useful stuff related to project #node-gotranslate and also update the existing contents where ever needed. However, following is a comprehensive list of what you should include: -
+ What the project is for
+ How to configure and install it
+ An example of how to use it or get it running
+ The license that the project is offered under
+ How to contribute to it


# Node-GoTranslate - An Introduction

> [node-gotranslate](https://github.com/itskdk/node-gotranslate), a next-generation, full-stack website localization framework.

**Node-GoTranslate** leverages upon the success of various popular packages and integrates these into a unique solution for localizing a remote website with minimal efforts.

##Node-GoTranslate - Major Components
The [node-gotranslate](https://github.com/itskdk/node-gotranslate) framework relies upon the following powerful components for its overall functionality: - 

1. **Website Crawler:** A component for crawling remote websites.
   **_Node-GoTranslate_** relies upon [node-simplecrawler]() package for its crawling functionality. In addition to this, It also consumes the packages such as #cheerio for executing custom JavaScript API of #node-gotranslate for extracting desired webpage contents, which needs to be localized using #node-gotranslate framework.

2. **Website Dumper:** A component for mirroring remote websites.

3. **Website Scrapper:** A component for scrapping contents from remote website
For website scrapping #node-gotranslate relies upon NodeJS built-in #http module for its scrapping functionality. In addition to this, It also consumes the packages such as #cheerio for executing custom JavaScript API of #node-gotranslate for extracting desired webpage contents, which needs to be localized using #node-gotranslate framework.

4. **Website Indexer:** A component for indexing website contents
For indexing localizable contents of website, #node-gotranslate relies upon the "Apache Solr" and uses #solr-client package for communicating with #node-gotranslate's Solr server.
