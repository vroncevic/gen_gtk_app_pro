# Generate App GTK C Project.

gen_gtk_app is shell tool for generating GTK C project.

Developed in bash code: 100%.

The README is used to introduce the modules and provide instructions on
how to install the modules, any machine dependencies it may have and any
other information that should be provided before the modules are installed.

[![GitHub issues open](https://img.shields.io/github/issues/vroncevic/gen_gtk_app.svg)](https://github.com/vroncevic/gen_gtk_app/issues)
 [![GitHub contributors](https://img.shields.io/github/contributors/vroncevic/gen_gtk_app.svg)](https://github.com/vroncevic/gen_gtk_app/graphs/contributors)

### INSTALLATION

Navigate to release [page](https://github.com/vroncevic/gen_gtk_app/releases) download and extract release archive.

To install modules type the following:

```
tar xvzf gen_gtk_app-x.y.z.tar.gz
cd gen_gtk_app-x.y.z
cp -R ~/sh_tool/bin/   /root/scripts/gen_gtk_app/ver.1.0/
cp -R ~/sh_tool/conf/  /root/scripts/gen_gtk_app/ver.1.0/
cp -R ~/sh_tool/log/   /root/scripts/gen_gtk_app/ver.1.0/
```

Or You can use docker to create image/container.

:sparkles:

### USAGE

```
# Create symlink for shell tool
ln -s /root/scripts/gen_gtk_app/ver.1.0/bin/gen_gtk_app.sh /root/bin/gen_gtk_app

# Setting PATH
export PATH=${PATH}:/root/bin/

# Generating GTK C project
gen_gtk_app SimpleTest
```

### DEPENDENCIES

This module requires these other modules and libraries:

* sh_util https://github.com/vroncevic/sh_util

### SHELL TOOL STRUCTURE

gen_gtk_app is based on MOP.

Shell tool structure:
```
.
├── bin
│   └── gen_gtk_app.sh
├── conf
│   ├── gen_gtk_app.cfg
│   ├── gen_gtk_app_util.cfg
│   ├── project_set.cfg
│   └── template
│       ├── authors.template
│       ├── autogen.template
│       ├── c_editorconfig.template
│       ├── changelog.template
│       ├── configure_ac.template
│       ├── copying.template
│       ├── c_source.template
│       ├── h_header.template
│       ├── main_source.template
│       ├── makefile_am_root.template
│       ├── makefile_am_src.template
│       ├── news.template
│       ├── readme.template
│       └── ui.template
└── log
    └── gen_gtk_app.log
```

### DOCS

[![Documentation Status](https://readthedocs.org/projects/gen_gtk_app/badge/?version=latest)](https://gen_gtk_app.readthedocs.io/projects/gen_gtk_app/en/latest/?badge=latest)

More documentation and info at:

* https://gen_gtk_app.readthedocs.io/en/latest/

:sparkles:

### COPYRIGHT AND LICENCE

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Copyright (C) 2018 by https://vroncevic.github.io/gen_gtk_app

This tool is free software; you can redistribute it and/or modify
it under the same terms as Bash itself, either Bash version 4.2.47 or,
at your option, any later version of Bash 4 you may have available.

:sparkles:

