# MetaWards R Package

This is a thin wrapper that makes it easy to install and use the 
[MetaWards](https://metawards.org) Python package within R.

Full installation instructions are [available here](https://metawards.org/install.html),
as well as a [R quick start guide](https://metawards.org/quickstart/index.html).

To install, open R or RStudio and type;

```
library(devtools)
install_github("metawards/rpkg")
metawards::py_install_metawards()
```

Once you have installed, you are all ready to continue with the 
[R quick start guide](https://metawards.org/quickstart/index.html).
