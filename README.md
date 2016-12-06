Old NYC
=======

Live site: http://www.oldnyc.org

The static content for this site lives in [oldnyc/oldnyc.github.io][1].
In particular you may be interested in the [giant JSON data file][2] which contains all
the data served on the site.

This repo contains Python code used to generate the data for the site.

To get going on development:

```bash
git clone git://github.com/danvk/oldnyc.git
cd oldnyc
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

See [nyc/howto.md](nyc/howto.md) for more details on how to perform specific tasks.

[1]: https://github.com/oldnyc/oldnyc.github.io/
[2]: https://github.com/oldnyc/oldnyc.github.io/blob/master/data.json
