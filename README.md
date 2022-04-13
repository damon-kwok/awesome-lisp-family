<a href="http://planet.lisp.org"><img src="https://th.bing.com/th/id/R.20a431e1f10c4beefeac4f4176ad77a0?rik=J9hD8shLPzFqZg&pid=ImgRaw&r=0" alt="Emacs Logo" width="80" height="80" align="right"></a>
[![Awesome](https://awesome.re/badge-flat2.svg)](https://www.patreon.com/DamonKwok)
[![Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://www.markdownguide.org/)
[![GitHub license](https://img.shields.io/badge/license-BSD%202%20Clause-2e8b57.svg)](https://github.com/damon-kwok/awesome-lisp-family/blob/main/COPYING)
[![Sponsor](https://img.shields.io/badge/Support%20Me-%F0%9F%92%97-ff69b4.svg)](https://www.patreon.com/DamonKwok)

# Awesome LISP Family

A list of lisp-flavored programming languages implemented on top of existing programming languages.


## Classification

- **Type-A**: Simple syntax mapping  
*These languages usually just provide s-expressions (parentheses) syntax and are translated to the target language without extra features/semantics. Also sometimes being called transpilers.*

- **Type-B**: Syntax and additional semantics  
*In addition to translating the syntax some additional features/semantics that are not present in the target language are added. Usually if a language does not fit in other category, it can be considered being a Type-B.*

- **Type-C**: [Clojure](https://clojure.org/)-like  
*Distintive syntax that besides parentheses also uses brackets and curly braces. Distinctive features are persistent data structures, namespaces and vars, protocols.*

- **Type-L**: [Common Lisp](https://en.wikipedia.org/wiki/Common_Lisp)  
*Implementing ANSI Common Lisp standard or being inspired by it.*

- **Type-S**: [Scheme](https://en.wikipedia.org/wiki/Scheme_%28programming_language%29)  
*Implementing some of RxRS standards or being inspired by Scheme.*

## Languages

Listed primarily by the language which can be used for interoperability / [FFI](https://en.wikipedia.org/wiki/Foreign_function_interface).

*Language section does not necessarily mean the language of the implementation. For example `Ferret` compiles into `C++` but the compiler is written in `Clojure`. Or `Carp` interops with `C` but it is mostly written in `Haskell`. In case of `SBCL` it contains only small amounts of `C`, but it is implemented almost entirely in `Common Lisp`.*

<!-- TOC depthFrom:3 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Multi Lang](#multi-lang)
- [Cobol](#cobol)
- [Common Lisp](#common-lisp)
- [Scheme](#scheme)
- [C/C++](#cc)
- [C#](#c)
- [Erlang](#erlang)
- [Fortran](#fortran)
- [Go](#go)
- [Java](#java)
- [JavaScript](#javascript)
- [Julia](#julia)
- [Lua](#lua)
- [Objective-C](#objective-c)
- [OCaml](#ocaml)
- [PHP](#php)
- [Perl](#perl)
- [Python](#python)
- [R](#r)
- [Rust](#rust)
- [Shell](#shell)
- [VHDL](#vhdl)
- [WASM](#wasm)

<!-- /TOC -->

### Multi Lang
| Name                                                           | Active                                                                                                                          | Type | Target |
|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Lux](https://github.com/LuxLang/lux)                          | [![last-commit](https://img.shields.io/github/last-commit/LuxLang/lux.svg)](https://github.com/LuxLang/lux)                     | B    |        |
| [Mal](https://github.com/kanaka/mal)                           | [![last-commit](https://img.shields.io/github/last-commit/kanaka/mal.svg)](https://github.com/kanaka/mal)                       | *1   |        |
| [STELLA](https://www.isi.edu/isd/LOOM/Stella/index.html)       |                                                                                                                                 | ?    |        |
| [Wax](https://github.com/LingDong-/wax)                        | [![last-commit](https://img.shields.io/github/last-commit/LingDong-/wax.svg)](https://github.com/LingDong-/wax)                 | *    |        |
| [Shen](https://shen-language.github.io/)                       | [![last-commit](https://img.shields.io/github/last-commit/Shen-Language/shen-cl.svg)](https://github.com/Shen-Language/shen-cl) | B    |        |
| [Zick Standard Lisp](https://github.com/zick/ZickStandardLisp) | [![last-commit](https://img.shields.io/github/last-commit/zick/ZickStandardLisp.svg)](https://github.com/zick/ZickStandardLisp) | ?    |        |

### Cobol
| Name                                         | Active                                                                                                                  | Type | Target |
|----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Cisp](https://github.com/lauryndbrown/Cisp) | [![last-commit](https://img.shields.io/github/last-commit/lauryndbrown/Cisp.svg)](https://github.com/lauryndbrown/Cisp) | L    |        |

### Common Lisp
| Name                                               | Active                                                                                                                            | Type | Target |
|----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [SBCL](http://www.sbcl.org)                        | [![last-commit](https://img.shields.io/github/last-commit/sbcl/sbcl.svg)](https://github.com/sbcl/sbcl)                           | L    |        |
| [Clasp](https://github.com/clasp-developers/clasp) | [![last-commit](https://img.shields.io/github/last-commit/clasp-developers/clasp.svg)](https://github.com/clasp-developers/clasp) | L    |        |
| [ECL](https://common-lisp.net/project/ecl/)        | [![last-commit](https://badgen.net/gitlab/last-commit/embeddable-common-lisp/ecl?.svg)](https://gitlab.common-lisp.net/ecl/ecl)   | L    |        |
| [CLISP](https://clisp.sourceforge.io/)             | [![last-commit](https://img.shields.io/github/last-commit/roswell/clisp.svg)](https://github.com/roswell/clisp)                   | L    |        |
| [Clozure CL](https://ccl.clozure.com/)             | [![last-commit](https://img.shields.io/github/last-commit/Clozure/ccl.svg)](https://github.com/Clozure/ccl)                       | L    |        |

See list of [additional implementations](https://www.cliki.net/Common+Lisp+implementation).

### Scheme
| Name                                                       | Active                                                                                                                                        | Type | Target |
|------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Racket](https://racket-lang.org/)                         | [![last-commit](https://img.shields.io/github/last-commit/racket/racket.svg)](https://github.com/racket/racket)                               | S    |        |
| [STklos](https://stklos.net/index.html)                    | [![last-commit](https://img.shields.io/github/last-commit/egallesio/STklos.svg)](https://github.com/egallesio/STklos)                         | S    |        |
| [Bigloo](https://www-sop.inria.fr/mimosa/fp/Bigloo/)       | [![last-commit](https://img.shields.io/github/last-commit/manuel-serrano/bigloo.svg)](https://github.com/manuel-serrano/bigloo)               | S    | native |
| [Gerbil](https://cons.io/)                                 | [![last-commit](https://img.shields.io/github/last-commit/vyzo/gerbil.svg)](https://github.com/vyzo/gerbil)                                   | S    |        |
| [Gauche](https://practical-scheme.net/gauche/)             | [![last-commit](https://img.shields.io/github/last-commit/shirok/Gauche.svg)](https://github.com/shirok/Gauche)                               | S    |        |
| [Chibi-Scheme](https://synthcode.com/wiki/chibi-scheme)    | [![last-commit](https://img.shields.io/github/last-commit/ashinn/chibi-scheme.svg)](https://github.com/ashinn/chibi-scheme)                   | S    |        |
| [Gambit](http://gambitscheme.org/)                         | [![last-commit](https://img.shields.io/github/last-commit/gambit/gambit.svg)](https://github.com/gambit/gambit)                               | S    |        |
| [Guile](https://www.gnu.org/software/guile/)               | [![last-commit](https://badgen.net/gitlab/last-commit/guile-git/guile-git?.svg)](https://gitlab.com/guile-git/guile-git)                      | S    |        |
| [Loko Scheme](https://gitlab.com/weinholt/loko)            | [![last-commit](https://badgen.net/gitlab/last-commit/weinholt/loko?.svg)](https://gitlab.com/weinholt/loko)                                  | S    |        |
| [Cisco Chez](https://www.scheme.com/)                      | [![last-commit](https://img.shields.io/github/last-commit/cisco/ChezScheme.svg)](https://github.com/cisco/ChezScheme)                         | S    |        |
| [Racket Chez](https://github.com/racket/ChezScheme)        | [![last-commit](https://img.shields.io/github/last-commit/racket/ChezScheme.svg)](https://github.com/racket/ChezScheme)                       | S    |        |
| [CHICKEN Scheme](https://www.call-cc.org/)                 | [![last-commit](https://img.shields.io/github/last-commit/spurious/chicken-core-mirror.svg)](https://github.com/spurious/chicken-core-mirror) | S    |        |
| [Cyclone](https://justinethier.github.io/cyclone/)         | [![last-commit](https://img.shields.io/github/last-commit/justinethier/cyclone.svg)](https://github.com/justinethier/cyclone)                 | S    |        |
| [Microscheme](https://ryansuchocki.github.io/microscheme/) | [![last-commit](https://img.shields.io/github/last-commit/ryansuchocki/microscheme.svg)](https://github.com/ryansuchocki/microscheme)         | S    |        |
| [Vicare](https://marcomaggi.github.io/vicare.html)         | [![last-commit](https://img.shields.io/github/last-commit/marcomaggi/vicare.svg)](https://github.com/marcomaggi/vicare)                       | S    |        |
| [Ikarus](https://launchpad.net/ikarus)                     | [![last-commit](https://img.shields.io/github/last-commit/hyln9/ikarus.svg)](https://github.com/hyln9/ikarus)                                 | S    |        |

See list of [additional implementations](http://community.schemewiki.org/?scheme-faq-standards#implementations) and [benchmarks](https://ecraven.github.io/r7rs-benchmarks/).

[The Development of Chez Scheme](https://legacy.cs.indiana.edu/~dyb/pubs/hocs.pdf)

### C/C++
| Name                                                   | Active                                                                                                                            | Type | Target |
|--------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Carp](https://github.com/carp-lang/Carp)              | [![last-commit](https://img.shields.io/github/last-commit/carp-lang/Carp.svg)](https://github.com/carp-lang/Carp)                 | B    |        |
| [Janet](https://janet-lang.org/)                       | [![last-commit](https://img.shields.io/github/last-commit/janet-lang/janet.svg)](https://github.com/janet-lang/janet)             | B    |        |
| [Cakelisp](https://github.com/makuto/cakelisp)         | [![last-commit](https://img.shields.io/github/last-commit/makuto/cakelisp.svg)](https://github.com/makuto/cakelisp)               | A    |        |
| [Dale](https://github.com/tomhrr/dale)                 | [![last-commit](https://img.shields.io/github/last-commit/tomhrr/dale.svg)](https://github.com/tomhrr/dale)                       | B    |        |
| [Owl Lisp](https://gitlab.com/owl-lisp/owl)            | [![last-commit](https://badgen.net/gitlab/last-commit/owl-lisp/owl?.svg)](https://gitlab.com/owl-lisp/owl)                        | S    |        |
| [Extempore](https://github.com/digego/extempore)       | [![last-commit](https://img.shields.io/github/last-commit/digego/extempore.svg)](https://github.com/digego/extempore)             | S    |        |
| [Maru](https://www.piumarta.com/software/maru/)        | [![last-commit](https://img.shields.io/github/last-commit/attila-lendvai/maru.svg)](https://github.com/attila-lendvai/maru)       | B    |        |
| [Liz](https://github.com/dundalek/liz)                 | [![last-commit](https://img.shields.io/github/last-commit/dundalek/liz.svg)](https://github.com/dundalek/liz)                     | A    |        |
| [Toccata](https://github.com/Toccata-Lang/toccata)     | [![last-commit](https://img.shields.io/github/last-commit/Toccata-Lang/toccata.svg)](https://github.com/Toccata-Lang/toccata)     | C    |        |
| [Lcc](https://github.com/saman-pasha/lcc)              | [![last-commit](https://img.shields.io/github/last-commit/saman-pasha/lcc.svg)](https://github.com/saman-pasha/lcc)               | A    |        |
| [PicoLisp](https://picolisp.com)                       | [![last-commit](https://img.shields.io/github/last-commit/picolisp/picolisp.svg)](https://github.com/picolisp/picolisp)           | B    |        |
| [Ferret](https://ferret-lang.org/)                     | [![last-commit](https://img.shields.io/github/last-commit/nakkaya/ferret.svg)](https://github.com/nakkaya/ferret)                 | C    |        |
| [C-Mera](https://github.com/kiselgra/c-mera)           | [![last-commit](https://img.shields.io/github/last-commit/kiselgra/c-mera.svg)](https://github.com/kiselgra/c-mera)               | A    |        |
| [FemtoLisp](https://github.com/JeffBezanson/femtolisp) | [![last-commit](https://img.shields.io/github/last-commit/JeffBezanson/femtolisp.svg)](https://github.com/JeffBezanson/femtolisp) | S    |        |

### C#
| Name                                                   | Active                                                                                                                          | Type | Target |
|--------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Clojure CLR](https://github.com/clojure/clojure-clr)  | [![last-commit](https://img.shields.io/github/last-commit/clojure/clojure-clr.svg)](https://github.com/clojure/clojure-clr)     | C    |        |
| [IronScheme](https://github.com/IronScheme/IronScheme) | [![last-commit](https://img.shields.io/github/last-commit/IronScheme/IronScheme.svg)](https://github.com/IronScheme/IronScheme) | S    |        |
| [Arcadia](arcadia-unity.github.io/)                    | [![last-commit](https://img.shields.io/github/last-commit/arcadia-unity/Arcadia.svg)](https://github.com/arcadia-unity/Arcadia) | C    |        |

### Erlang
| Name                                                    | Active                                                                                                                 | Type | Target |
|---------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Lisp Flavored Erlang](http://lfe.io/)                  | [![last-commit](https://img.shields.io/github/last-commit/lfe/lfe.svg)](https://github.com/lfe/lfe)                    | A2   |        |
| [Joxa](http://joxa.org/)                                | [![last-commit](https://img.shields.io/github/last-commit/lfe/lfe.svg)](https://github.com/joxa/joxa)                  | A1   |        |
| [Clojerl](https://github.com/clojerl/clojerl)           | [![last-commit](https://img.shields.io/github/last-commit/clojerl/clojerl.svg)](https://github.com/clojerl/clojerl)    | C    |        |
| [Kapok](http://kapok-lang.org/)                         | [![last-commit](https://img.shields.io/github/last-commit/kapok-lang/kapok.svg)](https://github.com/kapok-lang/kapok)  | C    |        |
| [scm](http://the-concurrent-schemer.github.io/scm-doc/) | [![last-commit](https://img.shields.io/github/last-commit/the-concurrent-schemer/scm.svg)](the-concurrent-schemer/scm) | S    |        |

### Fortran
| Name                                                                | Active                                                                                                               | Type | Target |
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|------|--------|
| [fscheme](https://genepi.qimr.edu.au/Staff/davidD/Scheme/SIOM.html) |                                                                                                                      | S    |        |
| [Schemetran](https://gitlab.com/codetk/schemetran)                  | [![last-commit](https://badgen.net/gitlab/last-commit/codetk/schemetran?.svg)](https://gitlab.com/codetk/schemetran) | A    |        |

### Go
| Name                                         | Active                                                                                                                  | Type | Target |
|----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Joker](https://joker-lang.org/)             | [![last-commit](https://img.shields.io/github/last-commit/candid82/joker.svg)](https://github.com/candid82/joker)       | C    |        |
| [Zygo](https://github.com/glycerine/zygomys) | [![last-commit](https://img.shields.io/github/last-commit/glycerine/zygomys.svg)](https://github.com/glycerine/zygomys) | B    |        |
| [ZYLISP](https://github.com/zylisp/zylisp)   | [![last-commit](https://img.shields.io/github/last-commit/zylisp/zylisp.svg)](https://github.com/zylisp/zylisp)         | A    |        |

### Java
| Name                                                   | Active                                                                                                                  | Type | Target |
|--------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|------|--------|
| [ABCL](https://common-lisp.net/project/armedbear/)     | [![last-commit](https://img.shields.io/github/last-commit/armedbear/abcl.svg)](https://github.com/armedbear/abcl)       | L    |        |
| [Clojure](https://clojure.org/)                        | [![last-commit](https://img.shields.io/github/last-commit/clojure/clojure.svg)](https://github.com/clojure/clojure)     | C    |        |
| [Kawa](https://www.gnu.org/software/kawa/)             | [![last-commit](https://badgen.net/gitlab/last-commit/kashell/Kawa?.svg)](https://gitlab.com/kashell/Kawa)              | S    |        |
| [Armed Bear Clojure](https://github.com/lsevero/abclj) | [![last-commit](https://img.shields.io/github/last-commit/lsevero/abclj.svg)](https://github.com/lsevero/abclj)         | C+L  |        |
| [PicoLisp](https://picolisp.com)                       | [![last-commit](https://img.shields.io/github/last-commit/picolisp/picolisp.svg)](https://github.com/picolisp/picolisp) | B    |        |

### JavaScript
| Name                                                         | Active                                                                                                                                    | Type | Target |
|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [BiwaScheme](https://www.biwascheme.org/)                    | [![last-commit](https://img.shields.io/github/last-commit/biwascheme/biwascheme.svg)](https://github.com/biwascheme/biwascheme)           | S    |        |
| [ClojureScript](https://clojurescript.org/)                  | [![last-commit](https://img.shields.io/github/last-commit/clojure/clojurescript.svg)](https://github.com/clojure/clojurescript)           | C    |        |
| [JACL](https://tailrecursion.com/JACL/)                      |                                                                                                                                           | L    |        |
| [LIPS](https://lips.js.org)                                  | [![last-commit](https://img.shields.io/github/last-commit/jcubic/lips.svg)](https://github.com/jcubic/lips)                               | S    |        |
| [RacketScript](https://github.com/racketscript/racketscript) | [![last-commit](https://img.shields.io/github/last-commit/racketscript/racketscript.svg)](https://github.com/racketscript/racketscript)   | S    |        |
| [Valtan](https://github.com/cxxxr/valtan)                    | [![last-commit](https://img.shields.io/github/last-commit/cxxxr/valtan.svg)](https://github.com/cxxxr/valtan)                             | L    |        |
| [Lumen](https://github.com/sctb/lumen)                       | [![last-commit](https://img.shields.io/github/last-commit/sctb/lumen.svg)](https://github.com/sctb/lumen)                                 | A    |        |
| [JSLisp](https://www.jslisp.org)                             | [![last-commit](https://img.shields.io/github/last-commit/6502/JSLisp.svg)](https://github.com/6502/JSLisp)                               | L    |        |
| [eslisp](https://github.com/anko/eslisp)                     | [![last-commit](https://img.shields.io/github/last-commit/anko/eslisp.svg)](https://github.com/anko/eslisp)                               | A    |        |
| [Parenscript](https://common-lisp.net/project/parenscript/)  | [![last-commit](https://img.shields.io/github/last-commit/ska80/parenscript.svg)](https://gitlab.common-lisp.net/parenscript/parenscript) | L    |        |
| [Wisp](https://github.com/Gozala/wisp)                       | [![last-commit](https://img.shields.io/github/last-commit/Gozala/wisp.svg)](https://github.com/Gozala/wisp)                               | C    |        |
| [Whalesong](https://www.hashcollision.org/whalesong/)        | [![last-commit](https://img.shields.io/github/last-commit/dyoo/whalesong.svg)](https://github.com/dyoo/whalesong)                         | S    |        |

### Julia
| Name                                                     | Active                                                                                                                        | Type | Target |
|----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [LispSyntax.jl](https://github.com/swadey/LispSyntax.jl) | [![last-commit](https://img.shields.io/github/last-commit/swadey/LispSyntax.jl.svg)](https://github.com/swadey/LispSyntax.jl) | A    |        |

### Lua
| Name                                   | Active                                                                                                              | Type | Target |
|----------------------------------------|---------------------------------------------------------------------------------------------------------------------|------|--------|
| [Fennel](https://fennel-lang.org/)     | [![last-commit](https://img.shields.io/github/last-commit/bakpakin/Fennel.svg)](https://github.com/bakpakin/Fennel) | A    |        |
| [Lumen](https://github.com/sctb/lumen) | [![last-commit](https://img.shields.io/github/last-commit/sctb/lumen.svg)](https://github.com/sctb/lumen)           | A    |        |
| [Urn](https://urn-lang.com/)           | [![last-commit](https://img.shields.io/github/last-commit/SquidDev/urn.svg)](https://github.com/SquidDev/urn)       | ?    |        |

### Objective-C
| Name                                               | Active                                                                                                                    | Type | Target |
|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------|--------|
| [nu](https://github.com/programming-nu/nu)         | [![last-commit](https://img.shields.io/github/last-commit/programming-nu/nu.svg)](https://github.com/programming-nu/nu)   | ?    |        |
| [DreamLisp](https://github.com/jsloop42/dreamlisp) | [![last-commit](https://img.shields.io/github/last-commit/jsloop42/dreamlisp.svg)](https://github.com/jsloop42/dreamlisp) | B    |        |

### OCaml
| Name                                             | Active                                                                                                            | Type | Target |
|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|--------|
| [Reason-Lisp](https://github.com/jaredly/myntax) | [![last-commit](https://img.shields.io/github/last-commit/jaredly/myntax.svg)](https://github.com/jaredly/myntax) | A    |        |

### Perl
| Name                                | Active                                                                                                  | Type | Target |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|------|--------|
| [Bel](https://github.com/masak/bel) | [![last-commit](https://img.shields.io/github/last-commit/masak/bel.svg)](https://github.com/masak/bel) | ?    |        |

### PHP
| Name                           | Active                                                                                                                      | Type | Target |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Phel](https://phel-lang.org/) | [![last-commit](https://img.shields.io/github/last-commit/phel-lang/phel-lang.svg)](https://github.com/phel-lang/phel-lang) | C    |        |

### Python
| Name                                         | Active                                                                                                                | Type  | Target |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-------|--------|
| [Hy](https://github.com/hylang/hy)           | [![last-commit](https://img.shields.io/github/last-commit/hylang/hy.svg)](https://github.com/hylang/hy)               | A1+C* |        |
| [Hissp](https://github.com/gilch/hissp)      | [![last-commit](https://img.shields.io/github/last-commit/gilch/hissp.svg)](https://github.com/gilch/hissp)           | A     |        |
| [Pixie](https://github.com/pixie-lang/pixie) | [![last-commit](https://img.shields.io/github/last-commit/pixie-lang/pixie.svg)](https://github.com/pixie-lang/pixie) | B     |        |

### R
| Name                                         | Active                                                                                                                    | Type | Target |
|----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------|--------|
| [llr](https://github.com/dirkschumacher/llr) | [![last-commit](https://img.shields.io/github/last-commit/dirkschumacher/llr.svg)](https://github.com/dirkschumacher/llr) | C    |        |

### Rust
| Name                                                 | Active                                                                                                                          | Type | Target |
|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [GameLisp](https://gamelisp.rs)                      | [![last-commit](https://img.shields.io/github/last-commit/fleabitdev/glsp.svg)](https://github.com/fleabitdev/glsp)             | B    |        |
| [ClojureRS](https://github.com/clojure-rs/ClojureRS) | [![last-commit](https://img.shields.io/github/last-commit/clojure-rs/ClojureRS.svg)](https://github.com/clojure-rs/ClojureRS)   | C    |        |
| [BLisp](https://ytakano.github.io/blisp/)            | [![last-commit](https://img.shields.io/github/last-commit/ytakano/blisp.svg)](https://github.com/ytakano/blisp)                 | B    |        |
| [Ketos](https://github.com/murarth/ketos)            | [![last-commit](https://img.shields.io/github/last-commit/murarth/ketos.svg)](https://github.com/murarth/ketos)                 | B    |        |
| [Rustly](https://github.com/timothypratley/rustly)   | [![last-commit](https://img.shields.io/github/last-commit/timothypratley/rustly.svg)](https://github.com/timothypratley/rustly) | C    |        |

### Shell
| Name                                             | Active                                                                                                                    | Type | Target |
|--------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Fleck](https://github.com/chr15m/flk/)          | [![last-commit](https://img.shields.io/github/last-commit/chr15m/flk.svg)](https://github.com/chr15m/flk)                 | A    |        |
| [Gherkin](https://github.com/alandipert/gherkin) | [![last-commit](https://img.shields.io/github/last-commit/alandipert/gherkin.svg)](https://github.com/alandipert/gherkin) | B    |        |

### VHDL
| Name                                            | Active                                                                                                                | Type | Target |
|-------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|------|--------|
| [VhdlLisp](https://github.com/domus123/vhdlisp) | [![last-commit](https://img.shields.io/github/last-commit/domus123/vhdlisp.svg)](https://github.com/domus123/vhdlisp) | ?    |        |

### WASM
| Name                                                       | Active                                                                                                                            | Type | Target |
|------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|------|--------|
| [Liz](https://github.com/dundalek/liz)                     | [![last-commit](https://img.shields.io/github/last-commit/dundalek/liz.svg)](https://github.com/dundalek/liz)                     | A    |        |
| [Schism](https://github.com/google/schism)                 | [![last-commit](https://img.shields.io/github/last-commit/google/schism.svg)](https://github.com/google/schism)                   | S    |        |
| [clj-wasm](https://github.com/roman01la/clj-wasm)          | [![last-commit](https://img.shields.io/github/last-commit/roman01la/clj-wasm.svg)](https://github.com/roman01la/clj-wasm)         | A    |        |
| [Arboreta WASM](https://github.com/Arboreta/arboreta-wasm) | [![last-commit](https://img.shields.io/github/last-commit/Arboreta/arboreta-wasm.svg)](https://github.com/Arboreta/arboreta-wasm) | ?    |        |

## Misc

- [Bel](http://paulgraham.com/bel.html) - self-hosted lisp dialect, see also markdown formatted [mirror](https://github.com/alephyud/bel)
  - [Language::Bel](https://github.com/masak/bel) - implementation of Bel in Perl 5, includes extensive test suite
  - [Chime](https://github.com/jeremyschlatter/chime/) - implementation of Bel written in Haskell
  - [Babybel](https://github.com/cookrn/babybel) - Ruby implementation of Bel
  - [Bel-sml](https://github.com/niyarin/bel-sml) - implementation written in Standard ML
- [uLisp](http://www.ulisp.com/) - Lisp for microcontrollers, fits into 2 Kbytes of RAM
- [CLJSL](https://github.com/IGJoshua/cljsl) - subset of Clojure compiled to GLSL for GPU programming
- A list of more [Clojure-like languages](https://github.com/chr15m/awesome-clojure-likes).
- Additional "write C in Lisp" [projects](https://www.reddit.com/r/lisp/comments/e10spm/a_list_of_various_lispflavored_programming/f8n6qxa/) (most of them not ready for a prime time).
- [Build your own lisp](http://www.buildyourownlisp.com/) - a book describing building a Lisp dialect
- See also list of languages  [implemented in Lisp](https://github.com/vindarel/list-of-languages-implemented-in-lisp).
- [Map of Common Lisp implementations](https://twitter.com/dk_jackdaniel/status/698157022483771392/photo/1)
- [Benchmarks of Scheme implementations](https://ecraven.github.io/r7rs-benchmarks/)
- [awesome-lisp-languages](https://github.com/dundalek/awesome-lisp-languages)
- [awesome-lisp-companies](https://github.com/azzamsa/awesome-lisp-companies)
- [awesome-clojure](https://github.com/damon-kwok/awesome-clojure)

## Contribute

Anything incorrect? Is there an interested project that is missing? Open an issue or PR to request adding a project to the list.
