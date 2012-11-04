
# tee

  `tee(1)`

## Usage

```javascript
var tee = require('tee');

src
  .pipe(tee(
    dest1,
    dest2,
    dest3
  ))
  .pipe(somewhereElse)
```

## Installation

```bash
$ npm install tee
# or
$ component install godmodelabs/tee
```

## API

### tee(destination, ...)

Creates a new through Stream that pipes all incoming data to each
`destination`-Stream.

## License

(MIT)
