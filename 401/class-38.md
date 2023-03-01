# Class 38 Reading Notes

## Intent Filters

What are the three criteria an activity’s intent filter must fulfill in order for a system to send an intent to that activity?
It must contain an action, it mustt contain data, and it must contain a category.

How does an activity retrieve the Intent that it was started by?
It needs to call getIntent().

Explain intents to a non-technical friend.
An intent allows you to go from one place to another if it's specified where you are and where you are going.

## Implicit vs. Explicit Intents

Compare and contrast implicit and explicit intents.
Explicit intent supplys either the target apps package name or component class name in order to satisy the intent.
You'll typically use these within your own app because you know the class names of your activities and services.

Implicit intent allows components from other apps to handle general actions.
It doesn't have the specificity that explicit intent has.

What is the primary information contained within an Intent?
Component Name,
Action,
Data,
Category,
Extras, and
Flags
