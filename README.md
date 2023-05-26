Let's try the graphite 😎😎😎

the new way of gitting? 🤔🤔🤔

## How to use

### Install the graphite

```
brew install withgraphite/tap/graphite

# if you use zsh use following command
gt completion >> ~/.zshrc
```

### Let's play

First clone the projects. (or make yourself)

Recommend for set prefix and disable day-prefix by graphtie, if you are using project managing tools (like jira etc.)

```
gt user branch-date --disable
gt user branch-prefix -s "1382810_" (ticket's number)
```

And make 'stack'

```
touch README.md
gt bc -am "add readme"

tocuh fizz
gt bc -am "add fizz"

touch buzz
gt bc -am "add buzz"
```

### Publish

Add PR in github

```
gt ss (or use 'gt ss -np' can pubish pr without confirm)
```

