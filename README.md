# golang-link-fetcher
A CLI to crawl a list of URLs and print out the set of unique links discovered

## Usage

```bash
# Using the go cli
go run main.go http://schier.co http://blog.schier.co
```

## Development

If you want to play around with the code, here's how you make changes

```bash
# Fetch dependancies
go get

# Build a binary
go build main.go

# Run the binary
./main <URL-1> <URL-2> ... <URL-n>
```

## Info

This code goes with a [tutorial]() on my blog.
