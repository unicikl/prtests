# prtests

The primary mechanism for managing state in Go is communication over channels. We saw this for example
with worker pools. There are a few other options for managing state though. Here we'll
look at using the `sync/atomic` package for _atomic counters_ accessed by multiple goroutines.