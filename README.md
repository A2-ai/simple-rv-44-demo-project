A simple project
==================


## Installation

```
curl -sSL https://raw.githubusercontent.com/A2-ai/rv/refs/heads/main/scripts/install.sh | bash

rv --version
```

## expected outputs


### summary

```
❯ rv summary
== System Information == 
OS: linux (x86_64)
R Version: 4.4

Num Workers for Sync: 4 (4 cpus available)
Cache Location: /cluster-data/user-homes/devin/.cache/rv

== Dependencies == 
Library: rv/library/4.4/x86_64/focal
Installed: 5/50

Package Sources: 
  PRISM: 0/45 binary packages
  builtin: 5/5 binary packages

Installation Summary: 
  PRISM: 45/45 in cache

== System Dependencies == 
Present: 1/2
Absent:
  pandoc

== Remote == 
PRISM (https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17): 770 binary packages, 784 source packages
```

### plan

```
❯ rv plan
+ base64enc (0.1-3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ bslib (0.9.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ cachem (1.1.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ cli (3.6.5, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ digest (0.6.37, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ dplyr (1.1.4, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ evaluate (1.0.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ farver (2.1.2, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ fastmap (1.2.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ fontawesome (0.5.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ fs (1.6.6, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17) with sys deps: ✓ make
+ generics (0.1.4, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ ggplot2 (3.5.2, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ glue (1.8.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ gtable (0.3.6, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ highr (0.11, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ htmltools (0.5.8.1, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ isoband (0.2.7, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ jquerylib (0.1.4, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ jsonlite (2.0.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ knitr (1.50, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17) with sys deps: ✗ pandoc
+ labeling (0.4.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ lifecycle (1.0.4, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ magrittr (2.0.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ memoise (2.0.1, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ mime (0.13, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ pillar (1.10.2, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ pkgconfig (2.0.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ purrr (1.0.4, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ R6 (2.6.1, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ rappdirs (0.3.3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ RColorBrewer (1.1-3, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ rlang (1.1.6, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ rmarkdown (2.29, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17) with sys deps: ✗ pandoc
+ sass (0.4.10, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17) with sys deps: ✓ make
+ scales (1.4.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ tibble (3.3.0, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ tidyselect (1.2.1, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ tinytex (0.57, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ utf8 (1.2.6, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ vctrs (0.6.5, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ viridisLite (0.4.2, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ withr (3.0.2, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ xfun (0.52, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
+ yaml (2.3.10, binary from https://prism.dev.a2-ai.cloud/rpkgs/stratus/2025-06-17)
```