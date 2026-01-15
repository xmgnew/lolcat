## About this fork

The original `c-lolcat` uses a time-based offset to determine the color phase.
When the program is invoked multiple times within a very short time window,
the generated color gradient remains the same.

This fork fixes that behavior by introducing a higher-resolution source for the
color offset, ensuring that each invocation produces a different color pattern,
even when called repeatedly in rapid succession.

## Installation 

Build loclcat with:
```
$ make lolcat
```
...and put the resulting binary at a place of your choice.
