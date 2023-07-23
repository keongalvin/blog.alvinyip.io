# blog.alvinyip.io

Repository for my personal [blog](https://blog.alvinyip.io/).

Theme based on <https://github.com/janraasch/hugo-bearblog/>.


### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.

#### Page

You can add **a new page** via running

```
hugo new my-new-page.md
```

#### Blog-Post

You can add **a new blog-post** via running

```
hugo new blog/my-new-post.md
```

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`style.html`](https://github.com/janraasch/hugo-bearblog/blob/master/layouts/partials/style.html)-file to find out which CSS-styles are applied by default.


---
Copyright © 2023, Alvin Yip
