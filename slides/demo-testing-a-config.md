##  Demo: Testing a Config

* Imagemagick Config

```
  <policy domain="delegate" rights="none" pattern="*" />
  <policy domain="coder" rights="none" pattern="*" />
  <policy domain="resource" name="time" value="30"/>
  <policy domain="system" name="memory-map" value="anonymous"/>
  <policy domain="cache" name="memory-map" value="anonymous"/>
  <policy domain="resource" name="memory" value="128MiB"/>
  <policy domain="coder" rights="read" pattern="{BMP,JPEG}" />
  <policy domain="coder" rights="read | write" pattern="{PNG,TIFF}" />
  <policy domain="system" name="max-memory-request" value="128MiB"/>
  <policy domain="resource" name="map" value="128MiB"/>
  <policy domain="resource" name="width" value="10MP"/>
  <policy domain="resource" name="height" value="10MP"/>
  <policy domain="resource" name="area" value="100MP"/>
  <policy domain="resource" name="disk" value="1GiB"/>
```

note:
    Put your speaker notes here.
    You can see them pressing 's'.
