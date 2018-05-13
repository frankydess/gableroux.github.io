# [gableroux.com](https://gableroux.com)

[![Build Status](https://travis-ci.org/GabLeRoux/gableroux.github.io.svg?branch=develop)](https://travis-ci.org/GabLeRoux/gableroux.github.io)

Hey there, welcome to the backstage of my website.

## install requirements

```bash
gem install bundle
bundle update
bundle install
npm i
npm run bower -- install
```

## Running this website locally

```bash
npm run gulp
```

## Deployment

See #11 this will be improved shortly

```bash
./script/deploy.sh
```

Now go read my posts!

## Contributing

> wubba lubba dub dub!

Found a typo? a broken link? Open [an issue](https://github.com/gableroux/gableroux.github.io/issues) or send me a pull-request! :rocket:

## Troubleshooting

### Error: `libsass` bindings not found. Try reinstalling `node-sass`?

More details on this [stackoverflow question](http://stackoverflow.com/questions/29461831/libsass-bindings-not-found-when-using-node-sass-in-nodejs).

```bash
npm uninstall --save-dev gulp-sass
npm install --save-dev gulp-sass@2
```

## License

[MIT](LICENSE.md) © [Gabriel Le Breton](https://gableroux.com)
