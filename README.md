# generate-serial-number
[![Build Status](https://travis-ci.org/hachi-eiji/generate-serial-number.svg?branch=master)](https://travis-ci.org/hachi-eiji/generate-serial-number)
## Description
simple generate serial number library.  
use Luhn algorithm when generate a serial number.
(for avoiding a user mistake input this)

## How to use

```
var generator = require('generate-serial-number');
var serialNumber = generator.generate(10); // 8380289275
```

## License
License under the [MIT](https://github.com/hachi-eiji/generate-serial-number/blob/master/LICENSE) license.
