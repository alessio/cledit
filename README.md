# cledit
Dumb changelog editor


```
$ ./cledit --help
usage: cledit [-w] [option]

Commands:
new                               Create new empty changelog.
add [-w] FILE SECTION STANZA      Add entry to a changelog file.
                                  Read from stdin until it
                                  encounters EOF.
convert FILE VERSION              Convert a changelog into
                                  Markdown format and print it
                                  to stdout.

    Sections:            Stanzas:
         ---                 ---
    breaking                gaia
    features             gaiacli
improvements            gaiarest
    bugfixes                 sdk
                      tendermint

Flags:
  -w	write result to (source) file instead of stdout
```
