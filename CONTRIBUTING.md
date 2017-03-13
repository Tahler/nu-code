# Contributing

Below is a list of tasks needed to be done if you would like to contribute

## Compilation API

- [ ] Detailed logging and errors with timestamps
- [ ] Stress test
- [ ] Add languages
  - [ ] Bash
  - [ ] Ruby
  - [ ] PHP
  - [ ] Haskell
  - [ ] R
  - [ ] D
  - [ ] Erlang
  - [ ] Clojure
  - [ ] Swift
  - [ ] Perl
  - [ ] Scala
  - [ ] F#
  - [ ] Common Lisp
  - [ ] Smalltalk
  - [ ] C
  - [ ] Kotlin
  - [ ] Scheme
  - [ ] Lua
  - [ ] Tcl
  - [ ] Fortran
  - [ ] Pascal
  - [ ] Nim
  - [ ] Delphi
  - [ ] Elm
- [ ] Unit testing
- [ ] Do not copy input files - Pipes?
- [ ] Split compiler image into many separate docker images
- [ ] Use `@types` over `typings`

## Submission API

- [ ] Detailed logging and errors with timestamps
- [ ] Use HTTPS
- [ ] Stress test
- [ ] Unit testing
- [ ] Use `@types` over `typings`

## Front-end

- [ ] Create competition page
- [ ] Checkmark next to completed problems
- [ ] Help / FAQ / Changelog
- [ ] User preferred language
- [ ] Redirect after login
- [ ] Log in through other providers
  - [ ] GitHub
  - [ ] Facebook
  - [ ] Google+
- [ ] User ratings
- [ ] Report problem has incorrect tests
- [ ] Limit leaderboard to one spot per person per language
- [ ] ng2 animation loading instead of a .gif
- [ ] Confirm leave without submitting
- [ ] Login required pages should open the log-in modal immediately
- [ ] Deleting problems, users, etc. moves to a deleted object rather than
      actually deleting; allows recovery through Firebase
- [ ] Competition exists / problem exists guards (currently gives 404)
- [ ] Use Router's Resolve to resolve data before activating route
- [ ] Unsubscribe observables: `onDestroy`
- [ ] "Podium" view on scoreboard after end
- [ ] Spiff up profile page
- [ ] Services employ caching
- [ ] Copyright footer
- [ ] Order, filter, and page-ify problems list
- [ ] Indication of authorization email sent
- [ ] Lazy load language templates / highlighting plug-ins
- [ ] Cleanup `usermgmt`
  - [ ] Create separate components for each action code
  - [ ] Redirect to respective components based on action code
- [ ] Two step verification: cool "step by step" display (see below)
```
(spinning/check/x) 1. Verifying your email...
(waiting/spin/check/x) 2. Placing you on the leaderboards...
```
- [ ] Playground area to test code before running
  - [ ] Load the example test case automatically

## Architecture

- [ ] Rewrite APIs in Go
- [ ] Rewrite front-end in React / ES2015
- [ ] Scale horizontally (ability to have multiple compilation servers, etc.)
