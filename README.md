# fire
Framework for Image Recognition results Experimentation and interpretation

This framework helps make image recognition libraries more usable. Currently the results from a call to an image recognition API return a list of potential matches with the probability of each match - this is immediately usable.

This framework will take additional inputs. It will take general "context" information pertinent to the image, as well as "user" information, which will be used to select filters to apply. Filters will be selected and applied to the {match, probability} pairs to help determine which results should be returned. The choice and order of which filters to apply may be varied based on the inputs, experimental seed, and other ongoing success metrics.
