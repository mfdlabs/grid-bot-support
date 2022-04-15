# What is this branch?
This branch is only used for tracking the releases tab, as the releases aren't technically published with source code, this branch is filled with just this README for that.

# Notice
The releases format will not be in the standard format of `yyyy.MM.dd-hh.mm.ss_{branch}_{gitShortHash}`, the parts after `yyyy.MM.dd` will be cut out, as this is used by developers only.

The format will be `yyyy.MM.dd{_${branch}}?`, where branch is optional, a non branch specified means `master` aka integration. If there are multiple releases to the same branch on the same day the format will be `yyyy.MM.dd-${revisionId}{_${branch}}?`.
