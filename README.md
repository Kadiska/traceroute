# Traceroute for Linux Files
source: https://sourceforge.net/projects/traceroute/

Traceroute developer is [Dmitry Butskoy]

All releases are licensed under the GPL v2.


## Branches organization

Time to time, a snapshot of Traceroute source's code si provided.

Those source should fed "upstream" branch *(generated files should be ignored by root .gitignore)*

please use snapshot name (such as "traceroute-2.1.0") as commit name in, to properly track code evolution.

"kadiska" branch, on the other hand will be reserved to kadiska changes made.

## Compilation
```bash
make
```

## Usage example

```bash
sudo traceroute/traceroute -T 8.8.8.8
```

Checkout [cli documentation](scamper.1.pdf)

