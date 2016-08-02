# Routing with ArcServer

### Use

Click the map at a starting point, then click an end point. A route will be drawn on the map and if you open your console (F12) you will see turn by turn directions. 

Currently, this example just uses two points, but with a slight modification, you can pass multiple stops - fix the 

```
map.on("click,function(){
        //allow more map clicks. 
        //Send them to getRoute()
        //Modify getRoute() to append them to the params string 
        }")
```

This example uses the Network Service at [NetCurrNet](http://gisdmd.cabq.gov/dmdview/rest/services/NetCurrNet/NAServer/Route/solve). 
