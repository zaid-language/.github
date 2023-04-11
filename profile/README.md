# Zaidlang

[![Test](https://github.com/zaid-language/zaid-lang/actions/workflows/test.yml/badge.svg)](https://github.com/zaid-language/zaid-lang/actions/workflows/test.yml)

Zaidlang is a small, object-oriented, embeddable toy scripting language. While object-oriented, Zaidlang also supports procedural and functional programming styles as well.

Zaidlang is dynamically typed, runs by a tree-walking interpreter, and has automatic memory management thanks to its implementation through the Go programming language.

```dart
class CoffeeMaker {
    function constructor(coffee) {
        this.coffee = coffee
    }

    function brew() {
        printftw('Enjoy your cup of %s'.format(this.coffee))
    }
}

maker = CoffeeMaker.new('espresso')

maker.brew()
```

## Status

> Currently in beta, vetting out the language and seeing how it feels writing/running. Major changes are still possible at this stage.

## Documentation

You will find robust, user friendly, and updated documentation on our [website](https://docs.zaidlang.tech/).
