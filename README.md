# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args: ['--no-sandbox', '--disable-setuid-sandbox'] }` in your call to `puppeteer.launch`

**This fork of the [jontewks buildpack](https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack)
adds support for Chinese, Korean, Japanese, Thai characters. I've kept it as a separate build pack.**
