# Global Solar Power Tracker

## Prerequisites

To use the project, you'll need the following:

- Composer installed globally
- Git
- PHP 8.4
- Some terminal/command-line experience

## What is the project about?

This is a small API to make using the Global Solar Power Tracker (currently an Excel spreadsheet) easier. 
I was inspired to create the API after reading through [a tutorial from a colleague of mine][twilio-tutorial].
In his tutorial, he made use of [a custom API][sneaks-api] that tracked changes to sneaker prices. 
However, I'm not a sneaker head, rather my interest is in renewable energy installation.
So, I sought out a source of data that tracks global renewable energy installation and came across _the Global Solar Power Tracker_ by [Global Energy Monitor][gem].
The information is provided in an Excel spreadsheet (which I don't like using).
So, I built this minimalist API in PHP to make it easier to interact with

## Getting Started

To get the API up and running, run the following commands:

```bash
git clone git@github.com:settermjd/global-solar-power-tracker-api.git
cd global-solar-power-tracker-api
composer install --no-dev --prefer-dist --optimize-autoloader
composer serve
```

Assuming the commands were successful, the API will be listening at http://localhost:8080.

[gem]: https://globalenergymonitor.org/ 
[global-solar-energy-tracker]: https://globalenergymonitor.org/projects/global-solar-power-tracker/ 
[sneaks-api]: https://github.com/druv5319/Sneaks-API
[twilio-tutorial]: https://www.twilio.com/en-us/blog/build-price-tracker-twilio-programmable-sms-node
