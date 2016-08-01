---
redirect_from: "/jquery-pjax"
layout: layout
title: PJAX
type: index
class: style-top
---

{::options parse_block_html="true" /}

<div class="row">

<div class="col-md-4">
## Feature

- <a href="{{ site.basepath }}demo/basic/1.html" target="_blank">Basic</a>
	- Multiple area update
	- Fallback area matching
	- CSS markless auto sync
	- Script markless auto load
	- [more](https://github.com/falsandtru/pjax-api#feature)
- Concurrency integration (unimplemented)
- Client-side load balancing (unimplemented)
</div>

<div class="col-md-4">
## Installation

```
$ npm i pjax-api spica localsocket
```

```html
<script src="/js/spica.js"></script>
<script src="/js/localsocket.js"></script>
<script src="/js/pjax-api.js"></script>
<script>
new window['pjax-api'].Pjax({
  areas: [
    '#header, #primary',
    '#container',
    'body'
  ]
});
</script>
```
</div>

<div class="col-md-4">
## API

[API]({{ site.basepath }}api/)

- [Pjax]({{ site.basepath }}api/pjax/)
- [Event]({{ site.basepath }}api/event/)
</div>

</div>

<div class="row">

<div class="col-md-4">
## License

[GPL-2.0](https://github.com/falsandtru/pjax-api#license)
</div>

<div class="col-md-4">
## Source

[GitHub: pjax-api](https://github.com/falsandtru/pjax-api)
</div>

<div class="col-md-4">
</div>

</div>