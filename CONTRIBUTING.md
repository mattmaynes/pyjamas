# How to contribute

## Testing

All public features need an associated Unittest test specification.

## Submitting changes

Please send a [GitHub Pull Request to mattmaynes](https://github.com/mattmaynes/pyjamas/compare)
with a clear list of what you've done (read more about
[pull requests](http://help.github.com/pull-requests/)). When you send a pull
request, please include a Unittest test to confirm the change is successful.
Please ensure that total test coverage is equal to or greater than the current
master coverage. Please follow the coding conventions (below) and make sure all
of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine
for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    >
    > A paragraph describing what changed and its impact."

## Coding conventions

These coding conventions are optimized for consistency and readability:

* Indentation should be a full tab (4 spaces)
* ALWAYS put spaces after list items and method parameters (`[1, 2, 3]`
, not `[1,2,3]`), around operators (`x += 1`, not `x+=1`), and around
hash arrows.
* Comment code only where you use non-standard syntax
* Strive for *functional* over *imperative*
* Use *map-reduce* over *recursion* over *loops* (no stinking loops!)
* Use *camelCase* for functions and variables (but try to avoid it)

