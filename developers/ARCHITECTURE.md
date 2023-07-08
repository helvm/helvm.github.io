# 📐 ARCHITECTURE

We have Spaghetti ARCHITECTURE inspired by Flying Spaghetti Monster.
We have six diffrent projects. And fix ways to parse code.

| Project | Parser | Direct goals | Indirect goals | Broad goals |
| ---     | ---    | --- | --- | --- |
| **[HelMA](http://helvm.org/helma)** | ReadP             | Collect Legacy Automata | Create common Stack Automaton | Imperative and unreadable languages |
| **[HelPA](http://helvm.org/helpa)** | AttoParsec        | Collect Legacy Assemblers | Create common Stack Assembler | Imperative and untypical languages |
| **[HelCT](http://helvm.org/helct)** | Happy Alex        | Build esoteric C Compiler | Collect C library | Imperative and statically typed languages |
| **[HelTC](http://helvm.org/heltc)** | Trifecta          | Build functional Language for Lambda Calculus | Collect algoritms, macros library and combinators | Functional and untypical languages |
| **[HelPS](http://helvm.org/helps)** | haskell-src / Own | Build self hosted Haskell | Compile Haskell to Esoteric Languages | Functional and statically typed languages |
| **[HelMS](http://helvm.org/helms)** | MegaParsec        | Build real Scheme in Haskell | Run Scheme in Esoteric Language | Imperative and dynamically typed languages |

## Style

| Procjects | HelMA, HelPA, HelCT | HelTC, HelPS, HelMS |
| --- | --- | --- |
| Style | Declaration (Real Haskell Style) | Expression (Scheme Style) |
| Application and composition | `$` Normal (`<<<` Right-to-left (Combinator Style)) | `&` Reversed (`>>>` Left-to-right (Pipe Style))|
| do notation | don't us, it is imperative | use, it is in Schema Style |
| List comprehension | No, never | Yes, of course |
| IO | Use IO, Use MonadIO and MockIO | Everything is `String -> String` |
| Prelude | Relude | Own |
| Language extensions | use many, use advanced feature of Haskell | try not to use it, use basic Haskell |
| Will we prescribe? | Maybe Rust? (Maybe APL? (Maybe BQN?)) |No, we can not! (Maybe Scheme? (Maybe PureScrip/Idris?)) |

## 🦄 🌈 ❤️ 💛 💚 💙 🤍 🖤
