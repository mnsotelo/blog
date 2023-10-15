---
title: "What is Inversion of Control(IoC) and Dependency Injection?"
date: 2023-10-15T00:00:00+00:00
# weight: 1
# aliases: ["/first"]
tags: ["design pattern", "spring"]
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: ""
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

## Description

Inversion of control is a software design pattern. Dependency injection is a type of Inversion of control, in some places these terms are used interchangeably.

Dependency injection allows to build cleaner and **loosely coupled components** by injecting dependencies and making them configurable using lightweight containers like Spring. This also allows creating unit tests easier by providing mocks or stubs as dependencies.

In the context of Spring framework, this is implemented using _Beans_ which alongside wiring methods allows to build object dependencies at runtime. 

## Resources

- https://martinfowler.com/articles/injection.html
- https://martinfowler.com/bliki/InversionOfControl.html
- https://drdobbs.com/tools/dependency-injection-testable-objects/185300375

