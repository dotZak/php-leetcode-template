# Leetcode Template for PHP

Use `composer create-project dotzak/leetcode {LOCAL NAME}` to create a new "project".

Replace `{LOCAL NAME}` with whatever you intend to name your local directory, e.g. _412_ for [Fizz Buzz](https://leetcode.com/problems/fizz-buzz/).

> NOTE:
>
> This template is meant to be installed once for each solution.
>
> It can definitely be used to house all solutions in one project, that's just not the intended use.

## Testing

In _tests/SolutionTest.php_ add the tests needed for the given solution.

Run `./vendor/bin/phpunit tests` to test using PHPUnit.

> NOTE:
>
> Use the `--testdox` flag to get a list of passed/failed tests by name, i.e.:
>
> ```sh
> ./vendor/bin/phpunit tests --testdox
> ```
