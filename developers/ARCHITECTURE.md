# 📐 ARCHITECTURE

We have Spaghetti ARCHITECTURE inspired by Flying Spaghetti Monster.
We have six diffrent projects. And fix ways to parse code.

| Project | Parser | Direct goals | Indirect goals | Broad goals |
| ---     | ---    | --- | --- | --- |
| **[HelMS](http://helvm.org/helms)** | MegaParsec        | Build real Scheme in Haskell | Run Scheme in Esoteric Language | Imperative and dynamically typed languages |
| **[HelPS](http://helvm.org/helps)** | haskell-src / Own | Build self hosted Haskell | Compile Haskell to Esoteric Languages | Functional and statically typed languages |
| **[HelTC](http://helvm.org/heltc)** | Trifecta          | Build functional Language for Lambda Calculus | Collect algoritms, macros library and combinators | Functional and untypical languages |
| **[HelCT](http://helvm.org/helct)** | Happy Alex        | Build esoteric C Compiler | Collect C library | Imperative and statically typed languages |
| **[HelPA](http://helvm.org/helpa)** | AttoParsec        | Collect Legacy Assemblers | Create common Stack Assembler | Imperative and untypical languages |
| **[HelMA](http://helvm.org/helma)** | ReadP             | Collect Legacy Automata | Create common Stack Automaton | Imperative and unreadable languages |
## Style

| Procjects                                                          | HelMS, HelPS, HelTC                             | HelCT , HelPA, HelMA                                 |
| ------------------------------------------------------------------ | ----------------------------------------------- | ---------------------------------------------------- |
| [Style](https://wiki.haskell.org/Declaration_vs._expression_style) | Expression (Scheme Style)                       | Declaration (Real Haskell Style)                     |
| Application and composition                                        | `&` Reversed (`>>>` Left-to-right (Pipe Style)) | `$` Normal (`<<<` Right-to-left (Combinator Style))  |
| do notation                                                        | use, it is in Schema Style                      | don't us, it is imperative                           |
| List comprehension                                                 | Yes, of course                                  | No, never                                            |
| IO                                                                 | Everything is `String -> String`                | Use IO, Use MonadIO and MockIO                       |
| Prelude                                                            | Own / RIO                                       | Relude                                               |
| Language extensions                                                | try not to use it, use basic Haskell            | use many, use advanced feature of Haskell            |
| Will we prescribe?                                                 | No, we can not! (PureScrip, BQN?)               | Maybe Rust? OCaml? Idris/Curry?                      |
| Package manager                                                    | Stack ?                                         | Cabal                                                |
| Other                                                              | Liquid Haskell                                  | Kowainik

## 🦄 🌈 ❤️ 💛 💚 💙 🤍 🖤
