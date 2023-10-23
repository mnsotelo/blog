---
title: "Data structure series - Array"
date: 2023-10-23T00:00:00+00:00
# weight: 1
# aliases: ["/first"]
tags: ["data structure", "golang"]
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

Array is one of the most popular data structures. You need to set declare an initial memory space. Memory allocation is contiguous.

Access and modification time complexity is constant O(1), the rest is O(N).

Furthermore, you can enhance your array with a dynamic approach, basically you don’t set the initial space, as long as your are adding new elements it will follow a strategy, one strategy is creating a new array with double the size and them move all the elements.


![Array memory allocation](/posts/ds-array/arrays_1.png "Array memory allocation")


```go
integerArray := [4]int{100, 101, 102, 103}

integerArray[0] = 1000
```

## Resources

- https://en.wikipedia.org/wiki/Array_(data_structure)
- https://go.dev/tour/moretypes/6

