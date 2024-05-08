# [IOS project1] XTF cryptotransaction log filter and preprocessor
This repo showcases skill and how little it sometimes takes to singlehandedly earn 11/15 pts.
This script filters and preprocesses transaction logs with known format, compressed, or not.
## Usage

    xtf [-h|--help] [FILTER] [COMMAND] USER LOG [LOG2 [...]

## Options

    COMMAND can be one of:
        list – prints transaction logs for the queried user.
        list-currency – lists currrencies user trades with.
        status – prints the currency portfolio grouped and sorted by name.
        profit – same as status, but with fictional gain.
    FILTR can be a combination of:
        -a DATETIME – after: only logs after this date are taken into account. DATETIME is of format YYYY-MM-DD HH:MM:SS.
        -b DATETIME – before: logs before this date (exccluding that date).
        -c CURRENCY – only transactions of that currency are queried.
    -h a --help go and try it if it ain't self-explanatory enough.
