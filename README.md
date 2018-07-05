
 **bigplay** - MPEG audio decoder and player
 Copyright (C) 2018 Risid

## Introduction

  `bigplay` is a command-line MPEG audio decoder and player based on madplay. For details about madplay, see https://github.com/robbie-cao/madplay

## Changes

  In order to meet the needs of the curriculum design:

  1. modify the shortcut keys.
```
    KEY_PAUSE = 'p',
    KEY_STOP = 's',
    KEY_FORWARD = 'f',
    KEY_BACK = 'b',
    KEY_TIME = 't',
    KEY_QUIT = 'q',
    KEY_INFO = 'c',
    KEY_GAINDECR = 'k',
    KEY_GAININCR = 'i',
```

  1. input a playlist file rather than a music file path.
    `madplay -f`

  2. simplifies the output.

  3. list loop playback is default.

## License

The source code is licensed under GPL v3. See the `LICENSE` for further details.

