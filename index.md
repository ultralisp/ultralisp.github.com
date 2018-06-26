Ultralisp is a quicklisp distribution, updated as fast as you can push
commits to the GitHub.

**Work in progress**, but you already can install some packages, like
quickdist or weblocks from this repository.

### Goals

* Provide to comminity a software repository which will be updated as fast as you can make `git push`.
* Make this repository easy to work with:

  * Lookup which releases was made;
  * Tag interesting projects;
  * Run tests for all dependent systems when some system was changed.

### How to use it

To use it, open your Lisp REPL and eval:

```lisp
(ql-dist:install-dist "http://dist.ultralisp.org/" :prompt nil)
```
