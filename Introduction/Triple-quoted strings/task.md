## Triple-quoted strings

You can use the convenient library functions 
[`trimIndent`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/trim-indent.html)
and [`trimMargin`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/trim-margin.html)
to format multiline triple-quoted strings
in accordance to the surrounding code.

Replace the `trimIndent` call with the `trimMargin` call
taking `#` as the prefix value, so that the resulting string didn't contain
the prefix character.