# How to Build this site:

1. clone to RStudio
2. library(rmarkdown)  # Probably not necessary as it should be built-in
3. Environment | History | **Build** tab > Build Website button
4. Manipulate some files
    - copy site_libs\bootstrap-3.3.5\flatly.min.css to /docs
    - delete docs/site_libs
    - copy /docs to libjohn.github.io repository
    - clone/commit/push libjohn.github.io
