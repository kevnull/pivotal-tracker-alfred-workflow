pivotal-tracker-alfred-workflow
===============================

A workflow for Alfred v2 (alfredapp.com) to add Pivotal Tracker stories directly.

Creates a story to Pivotal Tracker project. Copies resulting story url to clipboard.

SETUP
In the script, set the following:
$token = "INSERT YOUR TOKEN HERE";
Go to your name->profile in Pivotal Tracker to find this at the bottom

$requested_by = "INSERT YOUR NAME HERE";
The full name you have in Pivotal Tracker

$project = "INSERT PROJECT ID HERE";
The project id (the number in https://www.pivotaltracker.com/projects/<number>)


USAGE
pt <optional type> <name>

e.g.,
pt this is a feature
pt f this is a feature
pt feature this is also a feature
pt b this is a bug
pt c this is a chore

WISHLIST
Put multiple projects into the action selection
