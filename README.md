# ThingsIdoNotLikeAboutPerl6
brian d foy once had a Stack Overflow question that asked "What are 5 things that you HATE about your FAVORITE language". He said that if there weren't at least 5 things that you hated about your favorite language that you didn't know it very well.

Perl 6 is my favorite language. I could spend days telling you how awesome it is.

But I obviously don't know it well enough, because so far there are only a few things that I don't like:

1. `say` from Perl 5 is called `put` in Perl 6 and `say` is enough different to cause problems if you don't realize that.
2. Unused named parameters in method calls are silently ignored. Even https://github.com/nxadm/StrictNamedArguments does not fix except for on methods that you explictly declare `strict`.
3. It doesn't yet have an implementation that is as fast as Perl 5 for processing huge files (but it is getting faster).

But there are at least 10 reasons I can't leave Perl 6:

1. sub `MAIN` captures command line parameters into variables of your choice
2. sub `MAIN` automatically results in a `USAGE` statement when its parameters are not met
3. multi dispatch (even, or should I say especially, with `MAIN`)
4. The most effortless parallelism and async capabilities that I have ever seen.
5. named parameters require only one more character than positional parameters (i.e. `:` + `$x` = `:$x`).
6. Much improved regular expressions (e.g. Not needing `xms` at the end of every regex)
7. The ability to easily chain methods (like in Python)
8. Using unspace with chained methods so that they can line up vertically (unlike Python?)

By the way, did I mention how much I like `MAIN` subroutines?

Other things that I really like, even though I haven't yet used them:

* Maps are immutable versions of Hashes (Yea! Fewer accidents caused by mistyped keys!).
