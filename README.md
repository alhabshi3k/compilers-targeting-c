# Compilers targeting C

The following is a list of open source compilers that can generate C (or in some cases, C++) code.

| Project name/link | Language(s) supported | Notes |
|-------------------|-----------------------|-------|
| [ATS](http://www.ats-lang.org/) | ATS | Applied Type System (ATS) is a statically typed programming language that unifies implementation with formal specification. It is equipped with a highly expressive type system rooted in it. In particular, both dependent types and linear types are available in it. |
| [B::C](https://metacpan.org/pod/B::C) | Perl 5 | This compiler backend takes Perl source and generates C source code corresponding to the internal structures that perl uses to run your program. |
| [BaCon (Basic Converter)](http://basic-converter.org/) | Basic | BaCon is a free BASIC to C translator for Unix-based systems, which runs on most Unix/Linux/BSD platforms, including MacOSX. It intends to be a programming aid in creating tools which can be compiled on different platforms (including 64bit environments), while trying to revive the days of the good old BASIC. |
| [bc9Basic](https://sourceforge.net/projects/bc9basic/) | Basic | Can generate C or C++ code. Runs only on Windows but can generate code for *nix. A fork of [BCX](http://bcx-basic.sourceforge.net/) that outputs valid ISO/ANSI C. [Website archive](http://web.archive.org/web/20160405001529/http://bc9.bcxbasic.com/). |
| [Bigloo](http://www-sop.inria.fr/mimosa/fp/Bigloo/) | Scheme (R5RS) | Bigloo is a Scheme native-code compiler. It compiles Scheme code down to C, JVM bytecode or .NET bytecode. It includes type annotations, a unique object-oriented system based on CLOS, the Common Lisp Object System, and runtime performance is very close to C. |
| [bmx-ng](https://github.com/bmx-ng/bcc) | BlitzMax | A Monkey-derived BlitzMax to C transpiler. |
| [Carp](https://github.com/carp-lang/carp) | Lisp (Carp) | A statically typed lisp, without a GC, for real-time applications. |
| [CFortranTranslator](https://github.com/CalvinNeo/CFortranTranslator) | Fortran | A translator from Fortran90/Fortran77(ISO/IEC 1539:1991) to C++, Not C. |
| [Chapel](http://chapel.cray.com/) | Chapel | Chapel is a programming language designed for productive parallel computing on large-scale systems. Chapel's design and implementation have been undertaken with portability in mind, permitting Chapel to run on multicore desktops and laptops, commodity clusters, and the cloud, in addition to the high-end supercomputers for which it was designed. It can generate optimized C code. |
| [CHICKEN Scheme](http://www.call-cc.org/) | Scheme (R5RS) | |
| [Ciao](http://ciao-lang.org/) | Prolog | Ciao is a general purpose, multi-paradigm programming language in the Prolog family. The compiler can generate a .c file for each .pl file. |
| [cito](http://cito.sourceforge.net/) | Ć | A language for making portable libraries with a syntax like C#. Also targets Java, C#, JavaScript, ActionScript, Perl 5 and D. |
| [CLiCC](https://www.informatik.uni-kiel.de/~wg/clicc.html) | Common Lisp | Compiles a large strict subset of Common Lisp + CLOS to C. |
| [Critical Mass Modula-3](https://github.com/modula3/cm3) | Modula-3 | CM3 is the first open source release of the Modula-3 compiler and bundled software from Critical Mass,Inc. |
| [Cyclone](https://github.com/justinethier/cyclone) | Scheme (R7RS) | Cheney on the M.T.A. with native threads. |
| [Cython](http://cython.org) | Python | |
| [Céu](http://www.ceu-lang.org/) | Céu | It provides Structured Synchronous Reactive Programming. The compiler converts an input program in Céu to an output in C. |
| [EiffelStudio](https://www.eiffel.com/eiffelstudio/) | Eiffel | |
| [Embeddable Common-Lisp](https://common-lisp.net/project/ecl/) | ANSI Common Lisp | |
| [Epic](https://eb.host.cs.st-andrews.ac.uk/epic.php) | Epic | Epic is a simple functional Supercombinator language which compiles to reasonably efficient C code. It is currently used as a back end for [Idris](https://www.idris-lang.org/).|
| [Esotope Brainfuck Compiler](https://github.com/lifthrasiir/esotope-bfc) | Brainfuck | |
| [Euphoria to C Translator](http://www.rapideuphoria.com/e2c.htm) | Euphoria | |
| [f2c](http://www.netlib.org/f2c/) | Fortran 77 | F2c converts Fortran 77 source code in files with names ending in `.f' or `.F' to C (or C++) source files. |
| [f90toC](http://www.ncsa.illinois.edu/People/mdewing/f90toC/) | Fortran 90 | A Fortran 90 to C compiler. Note: This is a development version. It is not ready for general use as a Fortran compiler. |
| [fable](http://cci.lbl.gov/fable/) | Fortran 77  | Automatic fixed-format Fortran sources to C++ conversion, not C. |
| [FortranToCplusplus](https://github.com/uzipaz/FortranToCplusplus) | Fortran 90 | A C++ program that reads a Fortran 90 program and translates into a logically equivalent C++ program, not C. | 
| [Felix](http://felix-lang.org/) | Felix | Targets C++, not C. |
| [FreeBASIC](https://www.freebasic.net/) | Basic | A BASIC compiler for Microsoft Windows, DOS and Linux. It provides a high level of support for programs written for QuickBASIC. It is a self-hosting compiler that can produce console, graphical/GUI executables, dynamic and static libraries. It supports C libraries, style preprocessor, capable of multiline macros, conditional compiling and file inclusion, and C++ library partial. Programmers use and create libraries for C and many other languages. It can compile into intermediate file(s), eg. .asm, .c, .ll . |
| [Futhark](https://github.com/HIPERFIT/futhark) | Futhark | Purely functional data-parallel language generating OpenCL C |
| [Gambit](http://gambitscheme.org/) | Scheme (R5RS) | The Gambit Scheme system is a complete, portable, efficient and reliable implementation of the Scheme programming language. It consists of two main programs: interpreter and  compiler that generates portable C code. It conforms to the R4RS, R5RS and IEEE Scheme standards and implements all optional features. |
| [GCL](http://www.gnu.org/software/gcl/) | Common Lisp | GCL is the official Common Lisp for the GNU project. Its design makes use of the system's C compiler to compile to native object code. |
| [Genie](http://live.gnome.org/Genie) | Genie | Genie is another programming language supported by the Vala compiler with a syntax closer to Python. |
| [GHC](https://www.haskell.org/ghc/) | Haskell | [C backend](https://downloads.haskell.org/~ghc/7.6.3/docs/html/users_guide/code-generators.html) documentation page. |
| [GnuCOBOL](http://open-cobol.sourceforge.net/) | COBOL 2014 with extensions | The compiler can translate COBOL source files are into C files. |
| [gp2c](https://pari.math.u-bordeaux.fr/)| [PARI/GP](https://pari.math.u-bordeaux.fr/) | the GP-to-C compiler, combines the best of both worlds by compiling GP scripts to the C language and transparently loading the resulting functions into gp. |
| [Haxe](http://haxe.org) | Haxe | Has separate C++ and C targets |
| [Idris](http://www.idris-lang.org/) | Idris | A pure functional programming language with dependent types. |
| [Ivory](http://ivorylang.org/) | Ivory | A Haskell eDSL for safe systems programming. |
| [jhc](http://repetae.net/computer/jhc/) | Haskell 98 | The resulting code doesn't use a garbage collector. |
| [JX Objective-C](https://github.com/JX7P/JXobjC) | Objective-C (JX Dialect) | Object-oriented (Kayian School) language hosted on C |
| [Kit](https://www.kitlang.org/) | Kit | A statically typed procedural language with manual MM, traits, pattern matching, and metaprogramming designed with game development in mind. |
| [Language84](http://norstrulde.org/language84/) | Language84 | Language 84 is a programming language with a self-hosting compiler. |
| [mbeddr](http://mbeddr.com/) | mbeddr | A set of languages for embedded software engineering. |
| [Mercury](http://www.mercurylang.org/) | Mercury(~Prolog) | Mercury is a logic/functional programming language which combines the clarity and expressiveness of declarative programming with advanced static analysis and error detection features. It produce intermediate C code. |
| [M (Mosaic)](https://github.com/sal55/langs/tree/master/Mosaic) | M (inspired by Algol-68) | M is a systems language first devised for 8-bit Z80 systems in early 1980s, since evolved and now targeting 64-bit Windows machines using x64 processor. It builds to a single executable file that I usually call mm.exe, currently some 0.6MB, which includes a small set of libraries. (That is, the sources for the libraries are part of the executable.) This gives a tidy self-contained compiler. | 
| [MLton](http://mlton.org/) | Standard ML | MLton is an optimizing Standard ML compiler, Supports the full SML 97 language specification. It can compile to C code. |
| [Monkey 2](http://monkeycoder.co.nz/) | Monkey 2 | Targets C++, not C. |
| [Mrustc](https://github.com/thepowersgang/mrustc) | Rust | This project is an attempt at creating a simple rust compiler into intermidate C code. |
| [NectarJS](https://github.com/NectarJS/nectarjs) | JavaScript | The primary target is WebAssembly. [How to compile to C](https://github.com/NectarJS/nectarjs/issues/46#issuecomment-498532350). |
| [Nelua](https://nelua.io) | Lua | Nelua, stands for Native Extensible Lua, is a minimalistic, efficient, optionally typed, ahead of time compiled, meta programmable, systems programming language with syntax and semantics similar to Lua. It can work statically or dynamically depending on the code style and compiles to native machine code. Nelua compiles to C first then to the target native code. compiling on Windows is done using WSL or msys2. |
| [Nim](http://nim-lang.org) | Nim | Can generate C, C++ or Objective C code. |
| [Nit](http://nitlanguage.org/) | Nit | it is an expressive Object Oreinted language with a script-like syntax, a friendly type-system and aims at elegance, simplicity and intuitiveness. The syntax of Nit follows the Pascal tradition and is inspired by various script languages (especially Ruby). Its main objective is readability. |
| [Nuitka](http://nuitka.net/) | Python | |
| [OBNC](http://www.miasap.se/obnc/) | Oberon |  is a compiler implementation the latest version of the Oberon Prgramming language from 2016. OBNC translates source code written in Oberon to the lower-level programming language C. |
| [ocamlcc](https://github.com/ocaml-bytes/ocamlcc) | OCaml | Compiles OCaml bytecode to C. |
| [oi](https://github.com/hodefoting/oi/) | C with traits | Compiles to code that can be directly used from plain C. |
| [ooc](http://ooc-lang.org) | ooc | is a small programming language with a clear and concise syntax that compiles to C99. |
| [OpenDylan](http://opendylan.org/) | Dylan | Dylan is a multi-paradigm programming language that includes support for functional and object-oriented programming (OOP), and is dynamic and reflective while providing a programming model designed to support generating efficient machine code, including fine-grained control over dynamic and static behaviors. It generate intermidate C code. |
| [p2c](http://users.fred.net/tds/lab/p2c/) | Several Pascal dialects, including UCSD and Turbo Pascal; Modula-2. | Can generate C or C++ code. |
| [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) | Java bytecode | Use for the Java to iOS portability part of the [Codename One](https://www.codenameone.com/) project. |
| [pd_compiler](https://github.com/sharebrained/pd_compiler) | [Pure Data](https://puredata.info/) | Pure Data compiler, translates pd files into C code for compilation on embedded systems. Presently targeting ARM Cortex-M4F microcontrollers. |
| [purescript-native](https://github.com/andyarvanitis/purescript-native) | PureScript | Targets C++, not C. |
| [Py14](https://github.com/lukasmartinelli/py14) | Python | Targets C++, not C. |
| [Pythran](https://github.com/serge-sans-paille/pythran) | Python | Targets C++, not C. |
| [Ragel](http://www.colm.net/open-source/ragel/) | Ragel | Can generate C or C++ code. Compiles executable finite state machines from regular languages. |
| [RPerl](https://github.com/wbraswell/rperl) | RPerl, a restricted subset of Perl. | Targets C++, not C. Unrelated to RPython. |
| [RPython](https://rpython.readthedocs.org/en/latest/) | RPython, a restricted subset of Python. | Unrelated to RPerl. |
| [Sather](http://www.gnu.org/software/sather/) | Sather | Sather is an object oriented language which is designed to be simple, efficient, safe, and non-proprietary. It aims to foster the development of a large, freely available, high-quality library of efficient well-written classes for a wide variety of computational tasks. It was originally based on Eiffel, incorporating ideas and approaches from several languages. Sather code can be compiled into C code and can efficiently link with C object files. |
| [Scheme-to-C](https://github.com/akeep/scheme-to-c) | Scheme | Example nanopass compiler |
| [Seed7](http://seed7.sourceforge.net/) | Seed7 | Seed7 is a general purpose programming language that new statements and operators can be declared easily. Functions with type results and type parameters are more elegant than a template or generics concept. Object orientation is used where it brings advantages and not in places where other solutions are more obvious. The compiler translates Seed7 programs to C programs. |
| [Shedskin](https://github.com/shedskin/shedskin) | Python | Targets C++, not C. |
| [SLua](https://github.com/Neopallium/slua) | Lua | Static lua compiler - Compile Lua code into C code. |
| [SystemTap](http://sourceware.org/systemtap/) | SystemTap scripting language | SystemTap compiles kernel modules for monitoring Linux systems. |
| [ThinScript](https://github.com/evanw/thinscript) | ThinScript | A lower-level programming language inspired by TypeScript. ThinScript also compiles to JavaScript and WebAssembly. |
| [ts2c](https://github.com/andrei-markeev/ts2c) | JavaScript, TypeScript | Compiles a subset of JavaScript/TypeScript (ES3) to readable C89. |
| [TSP](https://github.com/tpoindex/tsp) | A typed subset of Tcl. | An experimental JIT. Compiles procedures written in a statically typed subset of Tcl to C or Java to accelerate Tcl programs. |
| [UbxBasic](https://sourceforge.net/projects/ubxbasic/) | Basic | Can generate C or C++ code. A fork of [BCX](http://bcx-basic.sourceforge.net/) that adds Linux support in addition to Windows. Uses Glib. |
| [Ur/Web](http://www.impredicative.com/ur/) | Ur/Web | Ur is a programming language in the tradition of ML and Haskell, but featuring a significantly richer type system. Ur is functional, pure, statically typed, and strict. Ur supports a powerful kind of metaprogramming based on row types. Ur/Web is Ur plus a special standard library and associated rules for parsing and optimization. Ur/Web supports construction of dynamic web applications backed by SQL databases. |
| [V](https://www.vlang.io/) | V |  Simple, fast, safe, compiled language for developing maintainable software. V can translate your entire C project and offer you the safety, simplicity, and 10-25x compilation speed-up. |
| [Vala](https://wiki.gnome.org/Projects/Vala) | Vala | Vala is a programming language using modern high level abstractions without imposing additional runtime requirements and without using a different ABI compared to applications and libraries written in C. Vala uses the GObject type system and has additional code generation routines that make targeting the GNOME stack simple. |
| [Zephir](http://zephir-lang.com/) | Zephir | A language for writing PHP extensions. |
| [ZZ](https://github.com/aep/zz) | ZZ (Drunk Octopus) | A safe dialect of C for embedded systems inspired by Rust. |

# C macro languages
* [C-Mera](https://github.com/kiselgra/c-mera), a simple source-to-source compiler that transforms s-expression notation to code in a C-family language.
* [LISP/c](https://github.com/eratosthenesia/lispc), a Common Lisp-based macrolanguage for C.

# See also
* [Cello](http://libcello.org/), a library for high-level programming in C.
* [Dynace](https://github.com/blakemcbride/Dynace), a portable, open-source object-oriented extension to the C, inspired by smalltalk and CLOS.
* [Object Oriented C (ooc)](http://ooc-coding.sourceforge.net/) kit is for those who want to program in an object orieneted manner, but stick on the good old C as well. ooc implements classes, single and multiple inheritance, exception handling.
* [Clue](http://cowlark.com/clue/), an ANSI C compiler targeting high level languages (Lua, JavaScript, Perl 5, C, Java, Common Lisp).
* [LLVM C backend resurrected](https://github.com/draperlaboratory/llvm-cbe).
* [luastatic](https://github.com/ers35/luastatic), a tool that builds standalone executables from Lua programs by embedding Lua code in C.

# Contributing

Your contributions are welcome! Please submit a pull request or create an issue to add a new compiler to the list.

# License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
