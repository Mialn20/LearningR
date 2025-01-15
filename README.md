# LearningR: Intro R course

This project is about learning git, Github and general R programming

# Brief description of folder and file contents

The following folders contain:

-   `data/`:
-   `data-raw/`:
-   `docs/`:
-   `R/`:

# Installing project R package dependencies

If dependencies have been managed by using
`usethis::use_package("packagename")` through the `DESCRIPTION` file,
installing dependencies is as easy as opening the
`LearningR.Rproj` file and running this command in the console:

```         
# install.packages("pak")
pak::pak()
```

You'll need to have remotes installed for this to work.

# Resource

For more information on this folder and file workflow and setup, check
out the [prodigenr](https://rostools.github.io/prodigenr) online
documentation.

# Extra

Use this to print the html file in chrome without margins:
```         
pagedown::chrome_print(input = here::here("docs/learning.html"),options = list(marginTop=0,marginBottom=0,marginLeft=0,marginRight=0))
```
