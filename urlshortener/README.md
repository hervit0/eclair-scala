# urlShortener #

## Build & Run ##

```sh
$ cd urlshortener
$ sbt
> jetty:start
> browse
```

If `browse` doesn't launch your browser, manually open [http://localhost:8080/](http://localhost:8080/) in your browser.

## Hot reload

In `sbt` console:
`~;jetty:stop;jetty:start`

## Troubleshooting

- `jetty:start` to compile new `template.scala.html` HTML template... Otherwise IntelliJ goes stupid
