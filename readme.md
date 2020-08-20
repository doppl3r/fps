# FPS Counter

A lightweight FPS counter using Javascript.

```
<script src="src/fps.js">
<script>
    var fps = new FPS();

    update = function() {
        ...
        fps.update();
        ...
    }

    render = function() {
        console.log(fps.getAverageFPS());
    }
</script>
```