# Twitter-Bots
**Sahil Dev, Jordan Foster, Joshua Goldberg, Gabriel Margolis, Mohammad Subhan**

Twitter bot classification project for CMSC396H, Fall 2020.

### Contents
- [Twitter-Bots](#twitter-bots)
    - [Contents](#contents)
  - [Background](#background)
  - [Problem Statement](#problem-statement)
  - [Scope](#scope)
  - [Files](#files)
    - [datasets](#datasets)
    - [docs](#docs)
    - [source](#source)
      - [analyze_text.ipynb](#analyze_textipynb)
      - [[classifier].ipynb](#classifieripynb)
      - [initialize_mib.ipynb](#initialize_mibipynb)
  - [Notes](#notes)
    - [Acknowledgements](#acknowledgements)
    - [Disclaimer](#disclaimer)

## Background

Twitter does not distinguish between bot accounts and real users, but reports estimate that nearly 48 million accounts on Twitter are run by bots. This wide network of bots has the ability to deceive real users. Bots have been found posting and responding to political tweets, and in 2016, about one-fifth of tweets about the U.S election came from a group of bot accounts. These bots influenced the content that real users saw on their timeline, altering the public perception current events and political figures. For example, bots may show artificial support or anger over the tweet of a politician or content of a news article, while other bots may simply spread misinformation.

## Problem Statement

Given features associated with a Twitter account, accurately determine whether the account is run by a bot.

## Scope

This work serves only to provide a true/false answer as to whether an account is run by a bot. We do not attempt to determine what purpose a bot serves, whether a bot acts maliciously, or if the associated account should be terminated.

## Files

### datasets

Stores datasets for use in training and testing.

### docs

Contains reports and documents detailing the research.

### source

Contains source files.

#### analyze_text.ipynb

Extract data from tweets.

#### [classifier].ipynb

Training and testing classifiers.

#### initialize_mib.ipynb

Main initialization work, data scraping, etc.

## Notes

### Acknowledgements

We would like to thank Dr. Dave Levin and Dr. Leilani Battle for contributing to the formation of this research group and providing excellent information and resources for doing research.

### Disclaimer

The data used for this research is from [MIB](http://mib.projects.iit.cnr.it/dataset.html). For privacy, the dataset used in this research will not be made available. Any other Twitter accounts and tweets used for training are fully public and are accessible to everyone.