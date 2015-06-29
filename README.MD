# Node-GoTranslate - An Introduction
> [node-gotranslate](https://github.com/itskdk/node-gotranslate), a next-generation, full-stack website localization framework.

**Node-GoTranslate** leverages upon the success of various popular packages and integrates these into a unique solution for localizing a remote website with minimal efforts.

##Node-GoTranslate - Major Components
The [node-gotranslate](https://github.com/itskdk/node-gotranslate) framework relies upon the following powerful components for its overall functionality: - 

+ **SiteDumper**, 
  a component for _mirroring or dumping_ remote websites for _offline preview or caching_ purposes.
+ **SiteCrawler**, 
  a component for _crawling_ remote websites.
+ **SiteIndexer**, 
  a component for _indexing_ website contents in _Apache Solr server_.
+ **SiteSearch**, 
  a component for providing _search as a service_ to remote or mirrored website.
+ **SiteViewer**, 
  a component for _previewing_ mirred website.
+ **PageScrapper**, 
  a component for _content scrapping_ from provided URL.
+ **PhraseExtractor**, 
  a component for _extracting or collecting translatable phrases_ from webpages.

---
### SiteDumper Component
> A component for _mirroring or dumping_ remote websites for _offline preview or caching_ purpose

**_Node-GoTranslate_** relies upon **TODO: Add/Refine relavent stuff**

---
### SiteCrawler Component
> A component for _crawling_ remote websites

**_Node-GoTranslate_** relies upon [node-simplecrawler](https://github.com/cgiffard/node-simplecrawler) package for its crawling functionality. 

**_Node-GoTranslate_** relies upon [node-simplecrawler](https://github.com/cgiffard/node-simplecrawler) package for its crawling functionality, for storing dumps on the file system it uses [Node's](https://nodejs.org/) built-in [**fs**] (https://nodejs.org/api/fs.html) module. In addition to this, It also consumes the packages such as [**cheerio**](https://github.com/cheeriojs/cheerio) for executing [**PhraseExtractor**](https://github.com/itskdk/node-gotranslate#phraseExtractor) JavaScript API for extracting webpage contents, which needs to be localized using **_Node-GoTranslate_** framework.

---
### SiteIndexer Component
> A component for _indexing_ website contents in _Apache Solr server_

**_Node-GoTranslate_** relies upon [solr-client](https://github.com/lbdremy/solr-node-client) package for indexing contents of website, into [Apache Solr](http://lucene.apache.org/solr/) server.

---
### SiteSearch Component
> A component for providing _search as a service_ to remote or mirrored website

As the name suggest, this compoent provides search-as-a-service to those websites, where site-level search feature is missing. This is an experimental component, which is purely based on Apache Solr for underlying functionality. 

### SiteViewer Component
> A component for _previewing_ mirred website

This component is mainly being used for showcasing offline or cached preview of mirror website upon request from various components and tools of **_Node-GoTranslate_** framework. 

---
### PageScrapper Component  
> A component for _content scrapping_ from provided URL

For website scrapping **_Node-GoTranslate_** relies upon [Node's](https://nodejs.org/) built-in [**http**](https://nodejs.org/api/http.html) and [**fs**] (https://nodejs.org/api/fs.html) modules. In addition to this, It also consumes the packages such as [**cheerio**](https://github.com/cheeriojs/cheerio) for executing [**PhraseExtractor**](https://github.com/itskdk/node-gotranslate#phraseExtractor) JavaScript API for extracting webpage contents, which needs to be localized using **_Node-GoTranslate_** framework.

---
### PageExtractor Component
> A component for _extracting or collecting translatable phrases_ from webpages

**_Node-GoTranslate_** provides an intellegent algorithm for extracting or collecting translatable phrases from webpages, which is an integral part of this component. 

It is the most important component of **_Node-GoTranslate_** framework, which is being used by following solutions at various levels: -

#### Client-side Solutions
+ **For end-users**, we have provided Browser Plug-ins for various popular web-browseres such as __Google Chrome__, __Mozilla Firefox__, __Internet Explorer__.
+ **For webmasters**, we provide Embeddable JavaScipt Code Snippet to be integrated into their website.

#### Server-side Components
+ The **_Node-GoTranslate_** framework's components such as __SiteCrawler__ and __SiteScrapper__ relies upon it.

---
### Developer/Maintainer
This project is being designed, developed and maintained by **@itskdk** - [Website](https://itskdk.github.io/) or [profile](https://github.com/itskdk).
