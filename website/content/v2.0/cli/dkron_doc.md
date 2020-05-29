---
date: 2019-10-10
title: "dkron doc"
slug: dkron_doc
url: /v2.0/cli/dkron_doc/
---
## dkron doc

Generate Markdown documentation for the Dkron CLI.

### Synopsis

Generate Markdown documentation for the Dkron CLI.
This command is, mostly, used to create up-to-date documentation
of Dkron's command-line interface for http://dkron.io/.
It creates one Markdown file per command with front matter suitable
for rendering in Hugo.

```
dkron doc [flags]
```

### Options

```
      --dir string   the directory to write the doc. (default "/tmp/dkrondoc/")
  -h, --help         help for doc
```

### Options inherited from parent commands

```
      --config string   config file path
```

### SEE ALSO

* [dkron](/cli/dkron/)	 - Open source distributed job scheduling system

###### Auto generated by spf13/cobra on 10-Oct-2019