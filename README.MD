# email Helper

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://github.com/SkycareOnskyHealth/email)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/SkycareOnskyHealth/email)

Auto emailing update helper.

## Getting Started!

```
oldemail := "1.1.2.1.9.5"
result, err := Updateemail(oldemail)
	if err != nil || result == "" {
		// handle error here
	}
	return result
```


### Installation

Request handler requires [Go](https://golang.org/) v1.11+ to run.

Install the package.

```sh
$ go get github.com/SkycareOnskyHealth/email
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT