# probot-datadog

> A GitHub App built with [Probot](https://github.com/probot/probot) that demonstrates sending data from Heroku to Datadog

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Heroku Datadog integration
```
# Setup the datadog specific buildpack ad index 1
> heroku buildpacks:add --index 1 https://github.com/DataDog/heroku-buildpack-datadog.git
```

To send heroku dyno and router metrics, setup the Heroku Datadog Drain service by following the instructions here: https://github.com/apiaryio/heroku-datadog-drain-golang

## Contributing

If you have suggestions for how probot-datadog could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2018 Tommy Byrd <tcbyrd@github.com>
