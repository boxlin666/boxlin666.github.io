---
title: Learning Golang
date: 2024-10-07 20:16:52
tags:
---

## WordCount

```Golang
package main

import (
	"strings"

	"golang.org/x/tour/wc"
)

func WordCount(s string) map[string]int {
	words := strings.Fields(s)
	wordCount := make(map[string]int)

	for _, word := range words {
		wordCount[word]++
	}

	return wordCount
}

func main() {
	wc.Test(WordCount)
}

```

