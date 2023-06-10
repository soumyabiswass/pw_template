# pw_template

A minimal starter repo for Pigweed projects.

## Setup

1. `git submodule update --init --recursive` to make sure all deps install?
1. `pw package install pico_sdk`
1. `gn args out` and then copy-paste:

       dir_pw_third_party_nanopb = "//third_party/nanopb"
       dir_pw_third_party_freertos = "//third_party/freertos"
       PICO_SRC_DIR = "//environment/packages/pico_sdk"

## Notes

https://pigweed.dev/pw_system/#target-bringup should link to the exact
stm32cube source code file

## Guidelines

* Minimal
* Complete
* Reproducible
* Enticing

https://stackoverflow.com/help/minimal-reproducible-example
