# Minimal Icecast Site
super minimal site for icecast, used for lightweight devices
(its super lightweight but ugly)

it grabs status.json.xsl from your icecast and either grabs `yp_currently_playing` or `title`
then fills out the station name and now playing from the json making it easy for you to scale this.

if u have any problems with the site, create an issue.
i will not help with station help or anything else.

## how to use

1. clone the repo
   ```bash
   git clone https://github.com/moinestifm/minimal-icecast-site.git
   cd minimal-icecast-site
   ```
3. open `index.html` or `index.min.html` using your preferred editor
4. replace the `STREAM_URL` with your icecast mount point:
5. change the `interval` if you want to reduce stress on icecast server

```js
const STREAM_URL = "http://yourserver:port/mountpoint";
```

please dont just steal this.. atleast credit stef or moinesti fm

