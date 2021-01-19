# testdata

Based on [json-server](https://github.com/typicode/json-server) and [my-json-server](https://my-json-server.typicode.com/)

## Data set
http://my-json-server.typicode.com/carballosa/testdata

## All
http://my-json-server.typicode.com/carballosa/testdata/posts

## One
http://my-json-server.typicode.com/carballosa/testdata/posts/1

## Filter
http://my-json-server.typicode.com/carballosa/testdata/posts?id=1&id=2

## Pagination
http://my-json-server.typicode.com/carballosa/testdata/posts?_limit=1&_page=2

## Sort
http://my-json-server.typicode.com/carballosa/testdata/posts?_sort=description&_order=desc

## Operators
http://my-json-server.typicode.com/carballosa/testdata/posts?id_gte=2
http://my-json-server.typicode.com/carballosa/testdata/posts?title_like=2

## Full-text Search
http://my-json-server.typicode.com/carballosa/testdata/posts?q=3

## Navigate Relationships
http://my-json-server.typicode.com/carballosa/testdata/posts/1/comments

## Embed childs 
http://my-json-server.typicode.com/carballosa/testdata/posts/1?_embed=comments

## Expand parent
http://my-json-server.typicode.com/carballosa/testdata/comments?_expand=post
