# SEO Best Practices Curated for Developers

Guidelines for new pages creation and additions/changes to existing content. Last update: **02.2022**

## Table of Contents

1. [Measuring performance](#1-measuring-performance)
2. [Tips and best practices](#2-tips-and-best-practices)
   - [Accessibility](#accessibility) - Help the browser and web crawlers understand your page
   - [Security and Compliance](#security-and-compliance) - Don't use deprecated or unsecured features
   - [Increase browser rendering speed](#increase-browser-rendering-speed)
   - [Caching resources by implementing an adequate cache policy](#caching-resources-by-implementing-an-adequate-cache-policy)
   - [Code quality](#code-quality)
   - [SEO](#seo)
3. [SEO tools](#3-seo-tools)
4. [Useful links](#4-useful-links)

## 1. Measuring performance

Google is the most used search engine worldwide and [Lighthouse](https://developers.google.com/web/tools/lighthouse) is the main tool provided by google to measure website performance. Google created [Page Speed Insights](https://pagespeed.web.dev/) that uses Lighthouse to measure your webpage performance and displays the results structured on sections as per image below.

> Explaining each section is beyond the scope of this documentation, if you want to read further, you can read [this blog](https://the-refinery.io/blog/walkthrough-of-a-google-lighthouse-report).

<br />

![PageSpeedPerformance](https://user-images.githubusercontent.com/80775241/155672539-a309fbea-1a0a-41e0-8180-6c0fb857cc5b.PNG)

<br />

The ideal result to achieve is green on each section on both Mobile and Desktop tabs. Hitting green on mobile devices is harder because, in general, they are slower than desktops, but mobiles are the most used devices in the world, this is a compelling reason to put all your efforts to reach green on all sections from the Mobile tab.

In order to help us achieve the best performance for our website, immediately after the scores we will find the **Opportunities** and **Diagnostics** sections that provides the necessary changes we need to apply in order to fix the scores.

<br />

![SEO](https://user-images.githubusercontent.com/80775241/155672320-cb3f3b67-fdd2-4340-97e2-4e67e94fcb1f.PNG)

<br />

Please do this check before each major deploy and make sure that you fix, where possible, all the Opportunities and Diagnostics suggestions.

## 2. Tips and best practices

### Accessibility

#### The `<noscript>` tag

#### The page defines a lang attribute

#### No empty elements

#### No 'refresh' <meta> tag

#### No empty "src" attribute

#### You specify a consistent label on your links

#### The main title of the page is the first stated title

#### Each form defines a submit button

#### All labels refer to an element

### Security and Compliance

#### Use only standard image formats

#### Your HTML response is not too heavy

#### No frameset, frame and noframes tags detected

#### No Java applets detected

#### Do not use <bgsound> tag

#### You do not use links to Word documents

#### No deprecated attributes are detected in the <body> tag

#### Your characters are encoded in UTF-8

#### No Flash resource

#### Define a Content Security Policy

#### SSL Certificate

#### Do all third-party resources deliver the right content?

#### Use HTTPS

#### All cookies are secure

### Increase browser rendering speed

#### Your HTML response is not too heavy

#### All your resources should be served from a consistent URL

#### Minify all your resources

#### The favicon is lightweight

#### Optimizing images

Reduce the files size using an optimizer
Serve Scaled images
Lazy loading is set

#### All resources should have a size < 1MB

#### No Mutation Events in your scripts

#### Your JavaScript resources don't block your page loading

#### A character set in the response HTTP Header

#### The page does not send to many cookies and their total size is not bigger then 100kB

#### You do not use CSS @import

#### You do not use a useless "http-equiv" <meta> tag

#### This page uses an appropriate number of DOM elements

#### You don't execute the same script several times

#### The page doesn't use client-side redirection

Redirects should be lightweight

#### Inject scripts efficiently

Data amount

### Caching resources by implementing an adequate cache policy

#### Do not use too long inline scripts

#### The 'Vary: Accept-Encoding' header is defined

#### Caching

#### You specify resource cache expiry headers

#### The cache duration is greater than 48 hours

### Code quality

#### Resources distribution by domain

#### Only reachable resources are requested

#### Don't use too much "prefetch" on the links

#### Override CSS properties and avoid side effects (CSS properties are overridden, CSS selectors are duplicated, CSS selectors are not too complex)

#### Don't abuse the css `!important` declaration

#### Separate the CSS styles from the HTML tags

#### Don't use superfluous CSS selectors

#### Harmonize the CSS colors

#### All resources should define their content type

#### IDs within the HTML code should be unique

#### `<img>` tags should use an alt attribute

### SEO

#### Specify a `<title>` tag and a `<meta>` description

#### The page description has a right size

#### The `<title>` tag is an appropriate length

#### Pages defines at least one `<h1>` and `<h2>` where possible

#### You use Open Graph properties

#### robots.txt file should be well defined

## 3. SEO tools

## 4. Useful links
