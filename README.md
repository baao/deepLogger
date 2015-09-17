# deepLogger

Very simple logger, add's the current time to the output and logs objects deep. Saves all that is being logged to a file, too. Since it is using moment, lodash and bluebird within only 20 lines of code don't use it in a production environment.


## Usage

    var log = require('deep-logger').deepLogger;
    log('hello world!' [, depth = 25]);

