# Fooocus 

## Pre-requisites
* Apolo cli. [Instructions](https://docs.apolo.us/index/cli/installing)

## Run Fooocus on Apolo

1. `$ git clone` this repo && `$ cd` into root of it.
2. `$ apolo-flow run fooocus` -- start Fooocus web UI

## Customizing the application

You can also customize the application by modifying the code and:

1. compiling your own container image with `$ apolo-flow build fooocus_apolo`
2. modifying the job `fooocus` in `live.yml` to use the image `${{images.fooocus_apolo.ref}}`