+++
title = "revealjs"
slug = "revealjs"
description = "present content as a reveal.js slide"
+++

This shortcode will format the enclosed markdow to render it with [reveal.js](http://lab.hakim.se/reveal-js/) at runtime (client-side)

Read more on [revealjs github repo](https://github.com/hakimel/reveal.js/#markdown).

## Usage

`revealjs` can use the following named parameters :

* theme
* transition
* controls
* progress
* history
* center


{{%warning title="Important" %}}Even if the enclosed content is a mardown, use `<` shortcode notation instead of the `%` notation {{%/warning %}}

### Content formating and slide delimiters

[read more on this here]({{% relref "page-slide.md"%}})

## Demo


{{<revealjs theme="moon" progress="true">}}

# In the morning

___


## Getting up

- Turn off alarm
- Get out of bed

___

## Breakfast

- Eat eggs
- Drink coffee

---

# In the evening

___

## Dinner

- Eat spaghetti
- Drink wine

___

## Going to sleep

- Get in bed
- Count sheep

{{</revealjs>}}

## Source :

{{%expand "Show code ..."%}}

```
{{</*revealjs theme="moon" progress="true"*/>}}

# In the morning

___


## Getting up

- Turn off alarm
- Get out of bed

___

## Breakfast

- Eat eggs
- Drink coffee

---

# In the evening

___

## Dinner

- Eat spaghetti
- Drink wine

___

## Going to sleep

- Get in bed
- Count sheep

{{</*revealjs*/>}}

```

{{%/expand%}}

* [{{%icon "sunglasses" %}} click here to view raw content](https://raw.githubusercontent.com/vjeantet/hugo-theme-docdock/master/exampleSite/content/shortcodes/revealjs.md)
## About project

Aenean ipsum justo, semper eu nisl ut, pretium tincidunt sem. Praesent et diam sit amet lacus lobortis dictum a id lacus. Quisque hendrerit sit amet turpis eu varius. Ut id lorem ac felis ultrices tincidunt. Pellentesque consequat arcu ac fringilla imperdiet. Phasellus pellentesque, sapien non pulvinar blandit, sapien ante aliquet felis, vel porttitor sapien ante in lacus. Fusce non urna aliquet, malesuada nibh vel, luctus urna. Phasellus ut lacus molestie, varius purus quis, malesuada lorem.

## Install

```bash
go get -u -v github.com/spf13/hugo
```

## Docs

https://godoc.org/github.com/spf13/hugo