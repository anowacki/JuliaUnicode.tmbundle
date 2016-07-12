# JuliaUnicode.tmbundle

## About

`JuliaUnicode.tmbundle` is a bundle for [TextMate 2](https://github.com/textmate/textmate)
which allows one to insert Unicode characters into documents by using the same
tab-completion bindings as in the Julia REPL.

For instance, to get a right arrow character (`→`), just type `\rightarrow` then
`<tab>`.
    
Almost all the symbols supported by the REPL are supported in TextMate.  Whether
or not you actually see the symbol of course depends on the Unicode support of
the display font you’re using.

## Install

To install, just clone this repo into
`~/Library/Application Support/Avian/Bundles` and TextMate will pick it up.

For example:

    mkdir -p "$HOME/Library/Application Support/Avian/Bundles" &&
        git clone https://github.com/anowacki/JuliaUnicode.tmbundle "$HOME/Library/Application Support/Avian/Bundles/JuliaUnicode.tmbundle"

## Licence

The JuliaUnicode.tmbundle software is licensed under under an MIT-style licence:

Copyright (c) 2016 Andy Nowacki (a.nowacki@leeds.ac.uk)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
