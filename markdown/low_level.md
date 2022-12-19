# What is low level?

Low level is a description in terms of Abstraction is like a category of abstraction but is more complex than that.

## Example

For example in terms of human language we can see an abstraction were latin is deeper level and for instance spanish mexican and british english is the higher level languages.

<table>
    <tr>
        <td>Mexican, Colombian</td>
        <td>British, Australian</td>
        <td>Canadian, French</td>
    </tr>
    <tr>
        <td>Spanish</td>
        <td>English</td>
        <td>French</td>
    </tr>
    <tr>
        <td colspan="3" align="center">Latin</td>
    </tr>
</table>

Human and programming language are different but this compare can be useful to understand what is a low level language in computer science. For this example Latin is low level language and all people that use Colombian spanish, or Australian english are using latin inclusively when they Even don't know that Latin exists.

Continuing with the same example I want change human language with Programming language.
<table>
    <tr>
        <td colspan="2">Typescript</td>
          <td></td>
    </tr>
    <tr>
        <td>Python, Ruby, Javascript, NodeJS</td>
        <td>Java, Scala Clojure</td>
        <td>Clojure</td>
    </tr>
    <tr>
        <td>C++, Rust, Golang, CPython</td>
        <td align="center">Java</td>
        <td></td>
    </tr>
    <tr>
        <td align="center" colspan="2">C Programming Language</td>
        <td align="center">Lisp</td>
    </tr>
    <tr>
        <td colspan="3" align="center">Assembly (Machine Code)</td>
    </tr>
</table>

This table is not 100% accurate of language hierarchy of programming language but it's not really important the idea is show that in programming language relationship is opposite way to human language for example latin is the more basic language and small and the other languages take part of them add your part and add up the a new part for example spanish grammar, rules etc.
in the other hand in programming language have a opposite behavior Assembly and C are more complex and responsibilities, grammar rules than the higher level programming language that are simpler, easier to use and flexible.

### It don't have sense

Both human and programming language put layer under others with the same approach but they have complete opposite result.

For example if you want mix this three language
Hypothetical scenario
```latin + spanish + french = new more complex language```

In the other hand in Programming language.

```assembly + C + CPython + interpreter + Garbage Collector + Optimizer = Python```

Python is the more simpler and used language at the moment.

It's impossible!! when we add more complexity and have more simpler language.
:face_with_spiral_eyes:.

If you still think it doesn't make sense, You are right.

Python is an complex ecosystem Compound of different systems,tools, languages and but the result is **syntax language** and at the same time really more complex system.

Both human and programming language have the same approach of have layers of and have the same result.
when you add more layer you have more layer you have more complex.

But in Computer science exist an principle **Abstraction**

For my opinion this is the reason and root of all modern problems since small pice of code to complex System software.

I call it an Abstraction paradox.

```Abstraction is used to make things more complex but make them look simpler.```

Modern language can use abstraction with 3 approach's.

- Solve a problem and share the solution functionality with out.
- Manage the problems and have trade off for example gain maintainability and lose speed.
- Abstract Don't solve any and delegate responsibilities to other layer manage the problem complexity.

### Why it's important in System programming?

All that you see above have directly impact in all type of software in not only C, assembly or low level.
because in all modern language use two last approach delegate and don't solve and or manage problem and have degradation of attributes of quality of software Starting with c.

If you read book c programming language second edition in preface you can read how it clarifies that C don't solve I/O, Concurrency, Memory Management, data structures library etc it responsibility was delegate to developers and higher levels langs.

all bug and fail in any systems will be in front backend python or assembly his cause of it delegation and the reason because all system experiment degradation of quality software attributes or trade off always that want speed, security and maintainability at the same time is impossible.

Low Level is the more important part of all system because directly impact of all attributes of quality of your software and systems and the all of use that and impact, Reliability, Maintainability, Security and all software.

High level  inherited all low level problems and try to solve it and hide the huge complex to users and pay high cost.

Historically anyone solve low level problems and make it easy until Rust Programming language that after appear to influenced language as C or C++, Zig, Carbon, Zig, Odin and etc.

## Appearance of Rust

Rust was designed by Graydon Hoare a person that see all that previous appreciations and design a new System programming language where don't exist trade off between abstraction and performance and you are not obliged to have degradation of speed if you want have secure, maintainability, stability, testability, observability and all this things easy.

this may seem not so revolutionary change and discover but really it is that.

It's the new modern system programming not is rust is the mindset you can achieve System, safe, secure, modern, easy to build using C, java or python use this new point of view.

Rust can solve many different problems with need more higher level languages it don't solve this problems avoid that problems born before when you write your code.

Concurrency, Memory Management, I/O, Security bugs, Testing, Interoperability, Distribution, Modularization and more since install cargo and compiler

It don't delegate responsibilities to other layer it solve all things and only share solution is a language with zero-cost abstraction.

## How it impact in modern system programming

I don't want waste time explain how it works before system and low level programming is plage of only old documentation, bad practice in terms of attributes of quality and more. I not want share errors only the good You can learn 60 years of history or the most efficient way that was found in those 60 years
