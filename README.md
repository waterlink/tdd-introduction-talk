<style>
img {
  height: 320px;
  float: left;
}
</style>

# Test-Driven Development Introduction

That TDD Fellow



![Oleksii Fedorov Photo](me.jpeg)

## Oleksii Fedorov

Software Craftsperson

@ Pivotal Labs - Berlin

That TDD Fellow

@waterlink000



## 3 Rules of TDD

1. You are not allowed to write a line of production code unless test fails.
2. You are not allowed to write more of a test, that is sufficient to fail.
3. You are not allowed to write more production code, that is sufficient to make the test pass.



## Red -> Green -> Refactoring

- `Red` by writing a failing test
- `Green` by writing enough of a production code to pass it
- Spend most of your time in `Refactoring` phase
- Repeat

Note:
You shape your system in refactoring phase, while keeping all the tests green.



## Benefits of TDD

- Maintainability, Flexibility, Extensibility
- Unparalleled Test Coverage
- Clean API
- Refactoring - 1st-class citizen
- Executable low-level documentation
- Long Term Speed Improvements

Note:
simple, elegant, modular code. bugs are found earlier (cheaper to fix). encourages end-user-point-of-view.



## Drawbacks of TDD

- Tests require maintenance
- Hard in legacy code
- Not trivial to do well
- Slower start
- Team needs to buy it

Note:
Tests keep code healthy -> they need care. The challenge to cover spaghetti code with tests. Going for the gold problem.



## My Personal Experience with TDD

3 years in and not going back!


### Green & Refactoring = Energy Boost

Note:
energy, motivation, happiness


### No Debugging

Note:
Maybe 2 hours per year total debugging time.


### Zero Fear

Code as a Modeling Clay.

Note:
I am not afraid to change the code and refactor anything in any way. It allows me to work with code as if it was a modeling clay (Plastilin).


### Enables Me & My Team

`./ship` instead of `git push`.


### QA Process

```bash
$ ./test && ./ship
Finished in 7.02343 seconds
17611 test cases, 0 failures

Your ship has sailed!
```



## Learn to do TDD Well?

Join Software Craftsmanship Community and attend Katas (Deliberate Practice):

In Berlin: [meetup.com/Software-Craftsmanship-Berlin](http://www.meetup.com/Software-Craftsmanship-Berlin/)

Software Craftsmanship Manifesto: [manifesto.softwarecraftsmanship.org](http://manifesto.softwarecraftsmanship.org/)

Completely suitable for Beginners and Experts!

Note:
It is completely free by the way.



## Summary | Q&A

1. Failing test first.
2. Only enough of a test to fail.
3. Only enough of a code to pass.

RED -> GREEN -> REFACTORING -> ...

Benefits vs Potential Drawbacks

Fun & Confidence



## Thank you!

Twitter: [twitter.com/waterlink000](https://twitter.com/waterlink000)

Github: [github.com/waterlink](https://github.com/waterlink)

Blog: [tddfellow.com](http://tddfellow.com)
