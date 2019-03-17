# Snapshot report for `test/index.js`

The actual snapshot is saved in `index.js.snap`.

Generated by [AVA](https://ava.li).

## shows up help message without any args

> Snapshot 1

    `Usage: teachcode <command> [options]␊
    ␊
    Options:␊
      -V, --version    output the version number␊
      -h, --help       output usage information␊
    ␊
    Commands:␊
      init             Initialize challenges␊
      submit           Submits current task␊
      fetchtask <key>  Fetches any task as per the key supplied␊
      showkeys         Shows keys of all the completed tasks␊
      showcommands     Shows all commands available`

## shows version with arg --version

> Snapshot 1

    '1.1.8'

## shows version with arg -V

> Snapshot 1

    '1.1.8'