# Overview
A package to search for synonyms

# Installtion

```
$ go get github.com/ryonakao/thesaurus
```

# Usage

```test.go
import "github.com/ryonakao/thesaurus"

thesaurus := &thesaurus.BigHuge{APIKey: 123}
syns, err := thesaurus.Synonyms("word")
	
```
