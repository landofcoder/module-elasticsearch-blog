## ElasticSuite Blog search for Ves Magento 2 Blog


This module connecting between each other [ElasticSuite](https://github.com/Smile-SA/elasticsuite) search extension and [Landofcoder](https://landofcoder.com/magento/magento-2-extensions.html) [Magento 2 Blog extension](https://landofcoder.com/magento-2-blog-extension.html)

It allows to index Magento 2 Blog posts into the search engine and display them into the autocomplete results, and also on the search result page.

### Requirements

* For version 1.x.x: Magento Community Edition 2.3.* - 2.4.* or Magento Enterprise Edition 2.3.* - 2.4.*

The module requires :

- [ElasticSuite](https://github.com/Smile-SA/elasticsuite)
- [Ves Blog](https://landofcoder.com/magento-2-blog-extension.html)

### How to use

1. Enable it

``` bin/magento module:enable Lof_ElasticsuiteBlog ```

3. Install the module and rebuild the DI cache

``` bin/magento setup:upgrade ```

4. Process a full reindex of the Blog Post search index

``` bin/magento index:reindex elasticsuite_blog_fulltext ```

Forked from Repo: [ComWrap ElasticsuiteBlog](https://github.com/comwrap/Comwrap_ElasticsuiteBlog)