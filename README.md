# Config

The [HoundCI](https://houndci.com) configuration repository for Vylpes' JS projects.

## About

This repository contains configuration files for HoundCI. The aim is to help enforce a specific styling across all of my repos. When you create a Pull Request for one of my projects Hound will check your code changes and check to see if your code abides by these styling rules.

Think a styling rule should be changed or added? Create the pull request here with the changes and I will review them!

ESLint Documentation for the rules can be found [here](https://eslint.org/docs/rules).

## Current Rules

Last Updated: 22nd October 2020
* Added "prefer-template"
* Added "comma-style" to be "last"

### Camelcase

Variable names should use `camelCase`, rather than `under_scores`.

### Brace Style: 1tbs

Braces should abide to "the one true brace style" (1tbs). Braces should be on the same line.

### Comma Dangle: Never

Commas should never dangle. There should not be a comma after the last item in a list.

### Comma Spacing: Not Before, Always After

There should not be a space before a comma but a space after it.

### Comma Style: Last

If a list goes across multiple lines, the comma should be the last character on the first line rather than the first character on the next line.

### Arrow Body Style: As Needed

The bodies of arrow functions should only use braces `{}` when required.

### Arrow Brackets: As Needed

The parameters of arrow functions should only use brackets `()` when required.

### Arrow Spacing: Always Before, Always After

There should be spacing either side of the arrow in the arrow functions.

### No Var

`var` shouldn't be used. Use `let` or `const` instead.

### Prefer Template

Strings should use templaye literals instead of String Concatenation.
