# copyedit

levenshtein-damerau x madlib

[![Madlib Project Badge](https://img.shields.io/badge/madlib-purple?logo=github&logoSize=auto)](//github.com/madlib-lang/madlib) <!-- $MADLIB.projectBadge -->
[![copyedit v0.0.3](https://img.shields.io/badge/v0.0.3-purple?label=version)](//github.com/brekk/copyedit) <!-- $MADLIB.json.version -->

```madlib
import CopyEdit from "copyedit"
import IO from "IO"

main = () => {
  IO.pTrace("distance!", CopyEdit.distance("madlib", "adlib")) // 1_b change
  IO.pTrace("nearest!", CopyEdit.nearest("bunch", ["brush", "crush", "shush", "suss", "hush", "mush", "rust", "hunch"])) // Just("hunch")
}
```
