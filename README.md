# Twitter Timeline Directive
An AngularJS directive of Twitter's Embedded Timeline with support for custom CSS.

## Requirements

* AngularJS
* jQuery
* A Twitter Widget Id ([https://twitter.com/settings/widgets/new](https://twitter.com/settings/widgets/new))

## Getting Started

1. Include the directive in your app
2. Go to [https://twitter.com/settings/widgets/new](https://twitter.com/settings/widgets/new) and create a new widget (timeline)
3. From the generated code, copy the Widget Id inside ``data-widget-id="XXXXXXXXXXXXX"``
4. Add this line to your HTML
    
> &lt;div twitter-timeline="TWITTER-WIDGET-ID" auto-resize="true" css-url="path/to/custom.css" data-tweet-limit="5"&gt;Loading tweets...&lt;/div&gt;

## Usage
> &lt;div twitter-timeline="TWITTER-WIDGET-ID" auto-resize="true" css-url="path/to/custom.css" data-tweet-limit="5"&gt;Loading tweets...&lt;/div&gt;

* ``twitter-timeline``
The Widget Id, get one here: [https://twitter.com/settings/widgets/new](https://twitter.com/settings/widgets/new).

* ``auto-resize``
If true, the div will resize to the same height as the iframe's content (the timeline).

* ``css-url``
The url to the CSS file that you want to apply on the timeline.

* ``data-tweet-limit``
Max number of tweets to show. For more information on custom attributes, check out the documentation on embedded Twitter timelines: [https://dev.twitter.com/docs/embedded-timelines](https://dev.twitter.com/docs/embedded-timelines).
