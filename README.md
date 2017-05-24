# Chrome Headless Stable 

Using the binary from the official Google Chrome PPA

![logo](https://lh4.googleusercontent.com/nOnP0piSjn9Wq3d821zhgtJbiL77VYLShSZdACIjTU86yydgurOchQFhpDIJhFouc4O0Pjc5QN4z-FvAgxaEvTdUsvEgADtFv_gkd4dNXsaLyynG3mzDtg2O51OB7YfbtDW49GFP "Logo")

```
$ docker run -it --rm -p=0.0.0.0:9222:9222 --name=chrome-headless -v /tmp/chromedata/:/data alpeware/chrome-headless-stable
```

Inspired by
- [National Library of Norway](https://github.com/nlnwa/docker-chrome-headless)

If this image is useful, please consider donating:

[![Donate!](https://donate.alpeware.com/static/donate.png?foo)](https://donate.alpeware.com/)
