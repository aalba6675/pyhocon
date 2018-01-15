# Branch to track fixes to papercuts in pyhocon

This personal combo branch tracks https://github.com/chimpler/pyhocon with a slew of fixes for papercuts merged. It should only be used for experiments.

All tox tests should not be broken (unless the tox test itself is b0rked, e.g, #141)

The source-of-truth is Java config-1.3.2.jar.

## Papercuts

* #137: from_dict option to create as root ConfigTree
* #125: a complex self-substitution
* #145: handle self-references in child nodes
* #141: the answer to the tests (and therefore the code) is wrong; fix both
* #110: merging configs: we also need to merge with all ConfigTree on the overriden_value linked list
*  #95: unexpected mutations of caller and fallback configs
