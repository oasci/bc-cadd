<h1 align="center">CADD</h1>

<p align="center">
    <a href="https://github.com/oasci/bc-cadd/actions">
        <img src="https://github.com/oasci/bc-cadd/actions/workflows/pages.yaml/badge.svg" alt="Build Status ">
    </a>
    <a href="https://creativecommons.org/licenses/by/4.0/">
        <img src="https://img.shields.io/badge/License-CC_BY_NC_SA_4.0-lightgrey.svg" alt="License">
    </a>
</p>

Welcome!
This online resource is designed to provide students, researchers, and professionals with a comprehensive introduction to the fascinating field of Computer-Aided Drug Design (CADD).
Here, you will find a wealth of information on the latest computational methods and tools used in drug discovery and development, as well as practical examples and case studies illustrating their application.
Whether you are new to CADD or an experienced practitioner, this resource aims to equip you with the knowledge and skills needed to harness the power of computational approaches in the quest for new and improved medicines.

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone git@github.com:oasci/bc-cadd.git

# Change directory
cd bc-cadd

# Install modules
hugo mod tidy

# Start the server
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.
