# Foundries.io Style Guide

This repository contains an implementation of the FoundriesFactory™ Platform style guide.
Use this with the [Vale](https://github.com/errata-ai/vale)([LICENSE](https://github.com/errata-ai/vale/blob/v2/LICENSE)) linter.

Installing from releases will also pull in the styles:

* [write-good](https://github.com/errata-ai/write-good); general good practices for writing in English
* [alex](https://github.com/errata-ai/alex); checks for insensitive or inappropriate language

## Overview

Vale is a linter for text; it checks a document for following a *style*.
In (and out) of Vale, a style is a set of rules, such as our Style Guide.
We can define these rules in a YAML file for Vale to use,
Rules go into a folder placed within the directory pointed to by `StylesPath`:

`Styles/Fio-docs/<rule_name>.yml`

`StylePath`, styles to use, and other options go into the configuration file.
This can be `_vale.ini` or `.vale.ini`, and Vale will look first in the current
directory, and then in the users home directory.

* [Writing styles for Vale](https://vale.sh/docs/topics/styles/)
* [Installing Vale](https://vale.sh/docs/vale-cli/installation/)
* [Setting up and Configuring Vale](https://vale.sh/docs/vale-cli/structure/)

Vale has [integrations](https://vale.sh/docs/integrations/guide/) with common editors/IDEs.

