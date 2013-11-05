# Highlight.js for rails 4.0

NB: Apologies to those who downloaded versions < 7.4.0.3; third times
a charm as they say.

This is my first gem and I am learning as I go along. I am reasonably
certain this version works, however you may want to wait a day or so
since my next job is to add some tests.

This is a minor update to chloerei/highlight_js-rails which I have
forked because :

1. I've nevered forked a repository before.
2. it hadn't been updated in a year and was 3 versions behind
highlight.js.
3. I've yet to create a gem. Its about time I learned.
4. It doesn't mention compatability with rails 4.0.

## Description

Rails pipeline wraper for highlight.js http://highlightjs.org/

## Install

In you Gemfile

```ruby
gem 'highlight_js-rails4'

# or

gem 'highlight_js-rails4', :git => 'git://github.com/chloerei/highlight_js-rails4.git'
```

Then `bundle install`

## Usage

application.js or appropriate layouts .js

```javascript
//= require highlight_js/highlight
//= require highlight_js/languages/ruby

hljs.initHighlightingOnLoad();
```

application.css

```css
*= require highlight_js/github
```
