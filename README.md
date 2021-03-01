# Cyclist

Cyclist cycles through a list of items added by a query string, promoting one item in the list per week. For instance, in the scenario of `?l=Pushups.Crunches.Running`, week 1 would promote `Pushups`, week 2 would promote `Crunches` and week 3 would promote `Running`. Week 4 would cycle back to `Pushups` and so on.

By default the promoted item changes on a Monday, but this can be offset with the `o` query string. eg. `o=2` would cause the the promoted item to change on a Wednesday instead.

Also, the interval of change doesn't have to be weekly. It can be any number of days specified by the `i` query string. eg `i=14` would cause the promoted item to change every two weeks instead.

## Demo

https://carlnewton.github.io/cyclist/?l=Tennis.Football.Badminton.Hockey&o=4
