# Snowplow Analytics GTM Templates

This is a collection of templates for GTM to make working with Snowplow Analytics a little easier. They are currently only in beta as I just whiped them up for my own purposes. You are free to re-use them, modify them, and/or redistibute them as you wish. If you could give me some of the credit that would be cool; if you make a valuable addition or change then please put in a PR so that others can benefit from it.

The templates are:


## Snowplow Analytics Tag

Designed to work like the Google Analytics tag that already exists. Can be used to add the base script to the page / fire a page view as well as re-used for structured or self-describing events.

__NOTE: You may have to edit the permisions of this template to allow it to access the global variable(s) for your tracker name(s) if they are not already on the list.__

## Snowplow Settings Variable

Also works very similarly to how the Google Analytics settings variable works. This is a variable you can use to configure most Snowplow settings in one place.

## Snowplow Context Variable

Allows you to create a self-describing JSON schema to attach to snowplow events in a user-friendly interface. Can be set to be undefined except in certain conditions.

## Snowplow Context List Variable

This variable is a function that will check return an array of the Snowplow Contexts you specify as long as those contexts are defined, can also be de-duplicated with another list if desired.