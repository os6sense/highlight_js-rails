# Highlight.js for rails 4.0

** UNTESTED

This is a minor update to chloerei/highlight_js-rails which I have
forked because :

1. I've nevered forked a repository before.
2. it hadn't been updated in a year and was 3 versions behind
highlight.js.
3. I've yet to create a gem. Its about time I learned.
4. It doesn't mention compatability with rails 4.0.

## Description

Rails pipeline wraper for highlight.js http://softwaremaniacs.org/soft/highlight/en/

## Install

In you Gemfile

```ruby
gem 'highlight_js-rails'

# or

gem 'highlight_js-rails', :git => 'git://github.com/chloerei/highlight_js-rails.git'
```

Then `bundle install`

## Usage

application.js

```javascript
//= require highlight_js/highlight
//= require highlight_js/languages/ruby

hljs.initHighlightingOnLoad();
```

application.css

```css
*= require highlight_js/github
```
