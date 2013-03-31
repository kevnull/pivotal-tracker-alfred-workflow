pivotal-tracker-alfred-workflow
===============================

A workflow for Alfred v2 (alfredapp.com) to add Pivotal Tracker stories directly.

Creates a story to Pivotal Tracker project. Copies resulting story url to clipboard.

##Setup
In the script, set the following:

Go to your name->profile in Pivotal Tracker to find this at the bottom

    $token = "INSERT YOUR TOKEN HERE";

The full name you have in Pivotal Tracker

    $requested_by = "INSERT YOUR NAME HERE";

The project id (the number in https://www.pivotaltracker.com/projects/{number})

    $project = "INSERT PROJECT ID HERE";


##Usage

    pt {optional type} {name}
    
Defaults to feature if no type is given. Acceptable types are "feature", "bug", and "chore" or their first character equivalent.

###Examples

    pt this is a feature
    
    pt f this is a feature
    
    pt feature this is also a feature
    
    pt b this is a bug

    pt c this is a chore

##Wishlist
Put multiple projects into the action selection
