Check captcha utility for web applications
==============================

## Related projects
[tornado](https://github.com/reganto/tornado)

## Utility

* `check captcha`

## Usage

get a `secret code` and `data-sitekey` from [google recaptcha](https://www.google.com/recaptcha/admin#list)

```bash
git clone https://github.com/reganto/CheckCaptcha
```

insert `secret code` to utility

then import utility to your project

finally add this lines to **your html**:
```html
<script src='https://www.google.com/recaptcha/api.js'></script>
```
```html
<div class="g-recaptcha" data-sitekey="YOUR DATA-SITEKEY"></div>
```



## Contributing

If you have improvements or bug fixes:

* Fork the repository on GitHub
* File an issue for the bug fix/feature request in GitHub
* Create a topic branch
* Push your modifications to that branch
* Send a pull request

## Authors

* [Reganto Blog](http://reganto.blog.ir)
* [Reganto Github](https://github.com/reganto)
