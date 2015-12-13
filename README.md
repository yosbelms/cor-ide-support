# Cor IDE Support

Syntax highlighters for the [Cor](http://yosbelms.github.io/cor) programming language

It contains packages for:

* Kate
* LiteIDE (via Kate)
* Notepad++

# Contributing

> We need help !

If you want to make a new highlighter or improve one of the existents, please clone the [repo](https://github.com/yosbelms/cor-ide-support), add your new highlighter or improve one of the existing, then make a pull request. There is some useful info below to start making your favorite IDE/Text Editor highlighter of [Cor](http://yosbelms.github.io/cor) syntax.

## Keywords

* `use`
* `class`
* `func`
* `me`
* `nil`
* `return`
* `if`
* `else`
* `for`
* `in`
* `switch`
* `case`
* `default`
* `continue`
* `break`
* `true`
* `false`

### Experimental keywords

* `try`
* `catch`
* `finally`
* `throw`

## Comments
### Multiline comment
Begins and ends with `---`

Example:
```
---
This is a documentation example
for Animal class
---
class Animal {
	
}
```

### Single line comment

Begins with `//` and ends in the next new line (`\n`) character

Example:
```
// example comment on foo
func foo() {
	
}
```

## Strings

Begins and ends with `'` char.

Example:
```
myStr = 'Hello World !'
```
Special characters can be escaped by preceding those characters with `\`.

Escape example:
```
myStr = 'I\'am a escaped text'
```

> This basic documentation is enough to make a simple *[Cor](http://yosbelms.github.io/cor) syntax colorizer*. Although if you want to get deep into [Cor](http://yosbelms.github.io/cor) lexic see the lexer at https://raw.githubusercontent.com/yosbelms/cor/master/src/bnf/cor.l for reference.