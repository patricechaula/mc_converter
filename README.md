# Multi-currency converter

## Platforms supported
- Android
- Web
- iOS

## Prerequisites

### expo-cli

For installation details goto https://docs.expo.io/workflow/expo-cli/

## Clone

`$ git clone https://github.com/ifelsegrandmaster/mc_converter.git`

## Install dependencies

`$ cd mc_converter`

`$ yarn install`

## Set API_KEY environment variable

Create a .env file in the project's root directory and add `API_KEY` environment variable

Create an account at https://exchangerate-api.com. Copy the API key from your dashboard. Paste it into your .env file

`API_KEY=<your_api_key>`

If you change your key. You have to start the metro bundler using the command below.  
`$ expo r -c` 

The `-c` option means clear metro bundler cache.

## Run
###  Android
`$ yarn android `
### Web 
`$ yarn web `



