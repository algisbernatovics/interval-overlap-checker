# Interval Overlap Checker

A compact PHP exercise for detecting whether intervals overlap.

## Learning Goal

Practice boundary-condition reasoning, small class design, and test coverage for a focused algorithm.

## Features

- Encapsulates overlap logic in a dedicated class.
- Includes PHPUnit tests for expected cases.
- Keeps the implementation small enough to inspect quickly.

## Complexity

- Time: `O(1)` for a single interval comparison.
- Space: `O(1)`.

## Example

Two intervals overlap when each interval starts before the other one ends:

```text
[1, 5] and [4, 8] => overlap
[1, 3] and [4, 8] => no overlap
```

## Tech Stack

- PHP
- Composer
- PHPUnit

## Run

```bash
composer install
vendor/bin/phpunit
```

## Project Structure

- `app/Overlap.php` - overlap detection logic
- `tests/TestOverlap.php` - test suite

## License

MIT License. See [LICENSE](./LICENSE).
