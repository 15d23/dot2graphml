# dot2graphml
This package contains a converter from DOT format used by GraphViz (http://graphviz.org) to variant of GraphML (http://graphml.graphdrawing.org/) used by yEd (http://www.yworks.com/en/products_yed_about.html). 

## Environment:

Mac:

```shell
brew install ghc
```



## Build:

ghc --make ./dot2graphml.hs



> Note:
>
> The dot file can't use subgraph cluster_XXX , I can't Fix this Problem