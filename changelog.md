# Promises/A+ Changelog

## [Version 1.1][] / 2013-02-??

- Specify that `onFulfilled` and `onRejected` must be called as functions, with no `this` value.
- Separate out the concept of a possibly-nonconformant "thenable" from the concept of a conformant "promise."
- Specify the Thenable Assimilation Procedure, instead of leaving the mechanism for adopting a thenable's state unspecified. In particular, the recursive nature of the now-specified procedure improves upon the naïve suggestion given in version 1.0.

## [Version 1.0][] / 2012-12-06

- Initial release. For differences from its predecessor, the Promises/A specification, see [Differences from Promises/A](differences-from-promises-a.md).


[Version 1.0]: https://github.com/promises-aplus/promises-spec/tree/1.0.0
[Version 1.1]: https://github.com/promises-aplus/promises-spec/tree/1.1.0
