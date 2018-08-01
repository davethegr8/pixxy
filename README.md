# pixxy

Takes a picture of a webpage using Puppeteer

### Global install

The best way to use this is with a global install. That prevents it from downloading Chromium everytime you use it.

```
» npm i -g pixxy
» pixxy
964ms saved example-com-2018-05-16T21-18-57-904Z.png
```

## Usage

The simplest version:

```
» npx pixxy
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
964ms saved example-com-2018-05-16T21-18-57-904Z.png
```

Arguments:

`--url [url]`

The page you want to screenshot

```
» npx pixxy --url http://example.com
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
934ms saved example-com-2018-05-16T21-20-51-702Z.png
```

`--filename [filename]`

Specify a filename to use

```
» npx pixxy --filename example.png
Downloading Chromium r555668 - 76.4 Mb [====================] 100% 0.0s
970ms saved example.png
```

`--width [width]`

Change the viewport width. Default is 1440, set to any value to change the page size.

`--verbose true`

More info

```
» npx pixxy --verbose true
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


