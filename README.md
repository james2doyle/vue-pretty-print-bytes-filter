# vue-pretty-print-bytes-filter

A filter for Vue.js to format bytes into a nice human-readable format. I pretty (no pun intended) much just stole this from [sindresorhus/pretty-bytes](https://github.com/sindresorhus/pretty-bytes).

### Install

Available through npm as `vue-pretty-print-bytes-filter`, or include as an inline script.

### Usage

Template:

```html
<em>{{ 1337 | prettyBytes }}</em>
```

Render:

```html
<em>1.34 kB</em>
```