# davethegr8/itap

Takes a picture of a webpage using Puppeteer

## Usage

The simplest version:

```
» npx github:davethegr8/itap
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
964ms saved example-com-2018-05-16T21-18-57-904Z.png
```

Arguments:

`--url [url]`

The page you want to screenshot

```
» npx github:davethegr8/itap --url http://example.com
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
934ms saved example-com-2018-05-16T21-20-51-702Z.png
```

`--filename [filename]`

Specify a filename to use

```
» npx github:davethegr8/itap --filename example.png
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
970ms saved example.png
```

`--verbose true`

More info

```
» npx github:davethegr8/itap --verbose true
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
1ms args { verbose: 'true',
  url: 'http://example.com',
  filename: null,
  _: [] }
494ms loading http://example.com
562ms viewport: { width: 1440, height: 446 }
995ms saved example-com-2018-05-16T21-22-30-982Z.png
995ms closing browser
```
