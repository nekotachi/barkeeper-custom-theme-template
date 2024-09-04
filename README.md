# Custom Templates for Barkeeper

This barebones respository contains everything you need to build
your custom templates for use with Nekotachi Ltd's Barkeeper
service.

## Requirements

You need to have Ruby >= 2.7 installed with bundler.

## Setup

1. Clone this repository
2. Run `bundle install`
3. Run `rake setup`

## Building your theme

All the theme source files live in the `/src` folder. Edit the HTML
and ERB content as you see fit.

You can test your theme with the command `rake server` to startup
a local development server which will complile and execute your
theme on the fly.

When you are ready to build your theme for deployment to Barkeeper,
run the command `rake build` and it will generate a `theme.zip` file
in the dist folder, ready for you to upload.

