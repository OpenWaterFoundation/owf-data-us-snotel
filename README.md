# owf-data-us-snotel #

This repository contains the [Open Water Foundation (OWF)](https://openwaterfoundation.org)
dataset files for Natural Resources Conservation Service (NRCS) SNOTEL stations.

This repository contains the workflow to create the GeoJSON files
from NRCS web service station lists.
The dataset files are also published on
[`data.openwaterfoundation.org`](https://data.openwaterfoundation.org)
and are used in data analyses and web applications.

The following sections provide a summary of the repository:

* [Repository Contents](#repository-contents)
* [How to Use the Data](#how-to-use-the-data)
* [License](#license)
* [Maintainers](#maintainers)

## Repository Contents ##

The repository contains the following:

```text
C:\Users\user/                              Windows user files.
/C/Users/user/                              Git Bash user files.
  owf-dev/                                  Open Water Foundation development files.
    data.openwaterfoundation.org/
      git-repos/
---------------- above folders are recommended --------------------
        owf-website-data/                   Repository that provides shared files to create dataset cloud landing page.
        owf-data-us-snotel/                 This repository.
          .gitattributes                    Git configuration file indicate repository configuration,
                                            in particular handling of line-ending and binary files.
          .gitignore                        Git configuration file to ignore files that should not be committed to the repository.
          README.md                         This file.
          data/                             The data files for the dataset, output from the workflow.
          workflow/                         Workflow files to process the dataset.
```

## How to Use the Data ##

The GeoJSON file in the `data` folder can be used directly by GIS and web mapping applications.

However, it is recommended to use the files served from the
[Colorado Farms](https://data.openwaterfoundation.org/country/us/nrcs/snotel/) dataset links.

## License ##

[Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)

## Maintainers ##

Steve Malers (@smalers, steve.malers@openwaterfoundation.org) is the primary contact.
