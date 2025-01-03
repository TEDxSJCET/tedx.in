# Simplest Link Shortener for Tedx Talks

Eg: 

[tedx.in/sjcet](https://tedx.in/sjcet) redirects to [tedx.sjcetpalai.ac.in](https://tedx.sjcetpalai.ac.in)

[sjcet.tedx.in](https://sjcet.tedx.in) redirects to [tedx.sjcetpalai.ac.in](https://tedx.sjcetpalai.ac.in)

## How to use?

Create a PR on this repository and we'll merge it.

`<repo>/<short_name>/index.html`
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="refresh" content="0; url=<your_url>" />
    <title>Redirecting...</title>
    <link rel="stylesheet" href="/style.css" />
  </head>
  <body>
    <div class="container">
      <h1>Redirecting...</h1>
    </div>
  </body>
</html>

```

Inside the PR comment, please provide your Email address and we'll contact you for further subdomain forwarding.
