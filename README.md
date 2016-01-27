# coCitation
finding papers in common in reference lists of scholarly corpu

Usually there are papers that everyone cites, but it can be hard to find them. Or, maybe you've read two great review papers and you're wondering what the foundational work is of the field.

This set of hacked together scripts will take an input of some number of papers and extract the cited papers in common, with a specified threshold. E.g. if there are 6 papers you're interested in and the threshold is set to 3, the only papers listed as centerpieces will be papers that have been cited 3+ times in that corpus.

