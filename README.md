# Heroku buildpack: srvdir

This is a [heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for [srvdir](http://srvdir.net).

## Usage

```
heroku create -b https://github.com/scottmotte/heroku-buildpack-srvdir

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/scottmotte/heroku-buildpack-srvdir.git

git push heroku master
```

## Recommended

Use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine this buildpack with others. For example, [carve-worker](http://github.com/scottmotte/carve-worker) does this.



