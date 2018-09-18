
# ellipsis
text "ellipsis" example in single line and multiple line.
https://d50000.github.io/ellipsis/

## single line

``` 
white-space:  nowrap;
overflow:  hidden;
text-overflow:  ellipsis;
width: 300px;
```

## multiple lines

```
overflow:  hidden;
display:  -webkit-box;
-webkit-line-clamp:  4;   //webkit has a support issue
-webkit-box-orient:  vertical;
width:  550px;
```


### note
 1. webkit-line-clamp support:
https://caniuse.com/#search=line-clamp

 2. other implement ways:
https://css-tricks.com/line-clampin/
