# Knowledge Pack
----
This Pack is designed for Cribl LogStream users at all levels of experience, and maintained by Cribl Solution Engineers. Every time we solve an interesting use case, our intent is to add it to this Knowledge Pack.
 
For legibility, the Knowledge Pack is set up according to a simple principle: 

**The Route name matches the Pipeline name matches the Sample name.**


# What's in the Pack? 
---

The LogStream techniques explained in the Pack include how to:

* Manipulate time using `strptime` and `strftime`.
* Split, trim, slice, and join data streams.
* Extract fields without losing data.
* Turn a JSON string into an object literal.
* Validate JSON data against a schema.
* Tag and route data using lookup tables, tags, and output routers.
* Use the Mask Function to decode data.
* Use the Mask Function to convert hex to numbers, and use the `C.Decode.hex()` function.
* Apply a Mask Function (md5) to any values in the object literal, using multiple wildcards.
* Process Cisco ASA events, using a Lookup Function to drop events, or to return a regex for extracting fields.
* Convert a UTF-16 dynamic-length array into a string, using Spread syntax.
* Extract exception and `calling_method` from a stack trace, using split and array references.

# What You Need (Prerequisites)
---
* A insatiable thirst for knowledge.

# What to Expect
---
* Knowledge of LogStream
* Power of the Pipeline

# Got a Problem?
---
And don't see it addressed here? We will solve it, put it in the Pack, and add you to our Contributors list!


# Using the Pack
---
The Knowledge Pack is easiest to use like this:

## Adjust the UI
---
When you first open the Knowledge Pack, the Routes tab should be selected. Use the column selector (<img valign="middle" width="24" height="18" src="https://github.com/criblpacks/cribl-knowledge-pack/blob/main/blob/kp-selector.png?raw=true">) to display the Description column and hide the Filter and Pipeline/Output columns. This lets you see and compare the Routes' Descriptions.

![Routes with Descriptions visible](https://github.com/criblpacks/cribl-knowledge-pack/blob/main/blob/kp-routes-selector.png?raw=true)

Once you display your first Pipeline, use the column selector to display Description and hide Filter. These display settings will now apply to all Pipelines.

![Pipelines with Descriptions visible](https://github.com/criblpacks/cribl-knowledge-pack/blob/main/blob/kp-pipeline-selector.png?raw=true)

## Workflow
---

Here's how to get started actually using the Pack's resources:

* Choose a Route that interests you.
* On the Pipelines tab, display the Pipeline of the same name.
* Open any Comment in the Functions list. The Comment gives you links to relevant LogStream docs. Open the docs in new browser tabs so you can refer to them as you work.
* Notice any Functions whose Description says **Leave off**, and read the explanation of why you should leave that kind of Function turned off (disabled).
* Turn off all the Functions.

Now, work through the Functions iteratively:

1. Turn on the first Function.
2. In the Sample Data tab, choose the sample whose name matches your chosen Route and Pipeline.
3. Notice what the Function does to the data – and think about what else you might want to do with it!
4. Turn on the next Function, repeat steps 3 and 4, etc.

## Release Notes
---
### Version 0.5 - 2021-07-28
Initial release!

Support for: Cribl LogStream Users

## Contributing to the Pack
---
Discuss this pack on our Community Slack channel [#packs](https://cribl-community.slack.com/archives/C021UP7ETM3).

## Contact
---
The authors and contributors to this pack are:
```
David Maislin <david@cribl.io>
Brendan Dalpe <bdalpe@cribl.io>
Jon Rust <jrust@cribl.io>
```

## License
---
This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).
