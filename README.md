Go Walk
=================

A minimal blog theme for [Hugo][hugo]

 - Minimal
 - Simple
 - Hackable


```
git submodule add https://github.com/saumya/saumya_go_walk.git themes/saumya_go_walk
```

In the New Hugo Project `config.toml` add below settings.

```
theme=['saumya_go_walk']

[params]
AuthorName = "Saumya Ray"
Subtitle = "Where there is a will, there is a way."
```



### command line

```
hugo server -D --port 80 --baseUrl=https://localhost:1313/2021/ 
```


 [hugo]: https://gohugo.io/
