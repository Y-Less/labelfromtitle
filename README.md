# open.mp-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that manages open.mp repositories.  It can:

* Auto-label issues based on a tagged name (`[Client]A bug`);
* ...

## Use

After installation, create `.github/autolabel.yml` in the default branch to enable it:

```yml
labels:
  - Server
  - Client
```

Then use the following pattern when naming issues:

`[Client]My Issue`

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Contributing

If you have suggestions for how open-mp could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2019 Y_Less <git@y-less.com> (open.mp)
