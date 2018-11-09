# spinel-produce

# background
I would like to provide a set of tools for downloading and importing data for the production of vector tiles in the hands-on session of the OSGeo.JP Workshop for the UN Vector Tile Toolkit.

# install
```shell
$ git clone git@github.com:un-vector-tile-toolkit/spinel-produce
$ cd spinel-produce
$ npm install
```

# configure
All configuration are stored in config/default.json.

```shell
$ vi config/default.json
```

# usage
## download source data
```shell
$ node download.js
```
This downloads GeoJSON text sequences from the following URLs.

- https://osgeo-jp.gitlab.io/spinel-data/gmlk20.ndjson.gz (6.4MB)
- https://osgeo-jp.gitlab.io/spinel-data/6-46-30.ndjson.gz (106MB)

# see also
- [RFC8142: GeoJSON Text Sequences](https://tools.ietf.org/html/rfc8142)
