
### Getting Set Up

1. Fork this repository on Github.
2. Clone *your forked repository* (not our original one) to your hard drive
3. `cd docs`
4. Initialize and start Docs.

```shell
bundle install
bundle exec middleman server
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!


### Deployment
- `doctl compute ssh jenkins@docs`
- `cd docs `
- `git fetch origin`
- `git rebase origin/master`
- `//git reset —hard orgin/master`
- `middleman build `


