# Show Braid

Quick javascript hack to show braids. Braid words are drawn with the rightmost generator corresponding to the bottom of the visualization.

To use, pass a braid in the query string as a number of strands followed by a list of generators:
```
show-braid.html?4:1,2,1,3,2,1,-3,-2,-3,-1,-2,-3
```

If you don't specify the strand count it will be automatically inferred:
```
show-braid.html?1,-5
```

## License

Public domain.
