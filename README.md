# Overview

This is the typescript based starter pack npm module to develop a parser/serializer for a language using [Chevortain](https://sap.github.io/chevrotain/docs/)
parser toolkit.

It bootstraps following constructs for a super simple sql dsl.

- lexer
- parser
- visitor
- serializer
- models
- diagram generation
- unit tests based on Jest

## Usage

- clone this repo

```
git@github.com:datasert/chevrotain-starter.git
```

- Change the package name and other things as appropriate

- Start implementing your language

## Unit Tests

Unit tests are must when you are developing new language. As you modify grammar, you want to make sure that it previous
texts. This pack comes with easy to use unit testing based on Jest.

To add tests, edit the `dsl-texts.ts` file with new dsl text, model it supposed to parse into and text after
serializing using couple of format options.

To run a single test, just add `only: true` property to that entry. This allows you to debug to fix issues.
