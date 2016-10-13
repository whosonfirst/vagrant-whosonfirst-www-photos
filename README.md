# vagrant-whosonfirst-www-photos

Everything you need to run the Who's On First Photo tool locally.

This is a work in progress. It probably doesn't work yet. But if you want to
try it out, try this:

```
mkdir -p /usr/local/mapzen
cd /usr/local/mapzen
git clone https://github.com/whosonfirst/vagrant-whosonfirst-www-photos.git
cd vagrant-whosonfirst-www-photos
make build
```

After the VM gets provisioned, you'll get SSH'd in. Type the following:

```
cd /usr/local/mapzen/whosonfirst-www-photos
make setup
```

## See also

* https://github.com/whosonfirst/whosonfirst-www-photos
* http://whosonfirst.mapzen.com/
