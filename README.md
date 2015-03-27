#Parallax micro plugin

![""](img/parallux2.gif)


###Usage

Very easy to use micro plugin, parallax effects is done by using css transform properties.

It depends on jQuery , you probably will use it in your project anyway.

```
var $image= $(" your img element");

$image.parallax({
horizontal:true,
shift : 3
});

```

####Options
+ horizontal:true - pretty much self explenatory
+ vertical :true - look above
+ shift : int - value passed to translate property, set between 1.5-3 for best results
