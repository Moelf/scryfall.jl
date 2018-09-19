# Scryfall.jl
*A Julia wrapper for basic functionality of https://scryfall.com --- a MtG all-in-one look-up site.*

| **Build Status**                                                                                |
|:-----------------------------------------------------------------------------------------------:|
| [![Build Status](https://travis-ci.org/Moelf/scryfall.jl.svg?branch=master)](https://travis-ci.org/Moelf/Scryfall.jl)|

**Installation**: note yet in Julia registry so you will need to clone this repo and follow [this guide](https://docs.julialang.org/en/v1.0.0/stdlib/Pkg/#Using-someone-else's-project-1)


## Basic Usage


```julia
using Scryfall

getOracle("Black lotus")
#"{T}, Sacrifice Black Lotus: Add three mana of any one color."

getImgurl("Black lotus")
# "https://img.scryfall.com/cards/normal/en/vma/4.jpg?1517813031"

getImgurl("Black lotus",setCode="LEB")
"https://img.scryfall.com/cards/normal/en/leb/233.jpg?1525123053"

```
