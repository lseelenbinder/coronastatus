# Coronastatus 
![](https://github.com/BustByte/coronastatus/workflows/test/badge.svg) 
> Report your health status to get a better overview of COVID-19 in your country (currently in 🇳🇴🇳🇱🇸🇰)


## What is this?

We don't know how many people have COVID-19. So we made a website where people can self-report symptoms. We plot the submissions on a map and show graphs with trends.

### Countries where Coronastatus launches

- 🇳🇴 Norway: https://coronastatus.no
- 🇳🇱 The Netherlands: https://coronastatus.nl
- 🇸🇰 Slovakia: https://coronastatus.sk
- ... want one for your country? Join our community: https://t.me/onzecorona

## Why?

The government is working on this, but they're too slow in getting something out fast.

## Mentions in the media

| Title                                                                       | Country        | URL       |
|-----------------------------------------------------------------------------|:--------------:|-----------|           
| Self-report system for monitoring COVID19 needs to be in place immediately! |     🇳🇴         | [Read here](https://www.aftenposten.no/meninger/debatt/i/P9ALzX/selvrapporteringssystem-for-overvaaking-av-korona-maa-paa-plass-naa-petter-bae-brandtzaeg) |
| Are you ill? Health services will soon let you self-report symtoms.         |     🇳🇴         | [Read here](https://www.bt.no/innenriks/i/QoAdAx/har-du-vaert-syk-snart-kan-du-hjelpe-helsemyndighetene-med-aa-registrer) |

## Who's behind this?

A bunch of developers from around the world that wanted to help out. This is not an official website from the health services.

## How can I contribute?

Join our Telegram group chat here: https://t.me/onzecorona or reach out on kontakt@bustbyte.no

Click on "Issues" in the menu above to see what we need help with.

## Start developing

Download and install [nodejs](https://nodejs.org),
[git](https://git-scm.com/downloads) and [yarn](https://yarnpkg.com/)

1. Clone the repository

`git clone https://github.com/BustByte/coronastatus`

2. Move into the newly cloned directory

`cd coronastatus`

3. Install dependencies with our package manager

`yarn`

4. Create a configuration file from the example provided in this repo

`cp config.example.json config.json`

5. Start the development webserver

`yarn dev`

6. Open your browser and navigate to http://localhost:7272/

7. Before you create a pull request run the linter. Warnings are ok, but errors should be fixed.

`yarn lint`
