# d3js
d3js notes

```
<script src="http://d3js.org/d3.v3.min.js" charset="utf-8"></script>
```
http://jsbin.com/diweyecure


```
d3.select("body").selectAll("p")
  .data([4, 8, 15, 16, 23, 42])
  .enter().append("p")
  .text(function(d) { return "I’m number " + d + "!"; });
    
```
