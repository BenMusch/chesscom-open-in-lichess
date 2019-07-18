# chesscom-open-in-lichess [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![devDependency Status][daviddm-dev-image]][daviddm-dev-url]

> Open chess.com analysis in the Lichess analysis board

#### [Install it from the Chrome Web Store]()

## Commands

- `npm start` to compile and watch the files for changes.
  After you ran `npm start` go in `chrome://extensions/`, enable `Developer mode` if you already haven't, click `Load unpacked extension...` and select the `build/` folder.
  Every time you change a file in the `src/` folder the extension is reloaded automatically.
- `npm run build` to just compile the files.
- `npm run bundle` to compile the files and put them in a `.zip`, ready to be uploaded to the Chrome Web Store.

## License

MIT © [Ben Muschol](https://github.com/benmusch)


[travis-image]: https://travis-ci.org/benmusch/chesscom-open-in-lichess.svg?branch=master
[travis-url]: https://travis-ci.org/benmusch/chesscom-open-in-lichess
[daviddm-image]: https://david-dm.org/benmusch/chesscom-open-in-lichess.svg
[daviddm-url]: https://david-dm.org/benmusch/chesscom-open-in-lichess
[daviddm-dev-image]: https://david-dm.org/benmusch/chesscom-open-in-lichess/dev-status.svg
[daviddm-dev-url]: https://david-dm.org/benmusch/chesscom-open-in-lichess/?type=dev

