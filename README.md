Hugo Site
=========

# Tips

* Use Goland to open the directory
* Assign *.html to "go template files" on "Settings -> Editor -> File Types"
* Add gotype for code completion in html file

```html
<!doctype html>
{{- /*gotype: github.com/gohugoio/hugo/hugolib.pageState*/ -}}
<html lang="en">
</html>
```

* Customized models for template variables

```html
<!doctype html>
{{- /*gotype: hugo-site/stubs.PageInfo*/ -}}
<html lang="en">
</html>
```

# References

* Hugo: <https://gohugo.io/>
* Go template: <https://golang.google.cn/pkg/text/template/>
* Golang Templates CheatSheet: <https://curtisvermeeren.github.io/2017/09/14/Golang-Templates-Cheatsheet>
* Toml: <https://toml.io/>
* How to start a blog using Hugo: <https://flaviocopes.com/start-blog-with-hugo/>

