# MonkeyBench

The preliminary qualification exam for Team 1280's programming and
controls lead positions.

---

<img src="./ferris.png" alt="Ferris the crab" width="100px">

**Proudly powered by Rustacean technology**  
_We are not affiliated with [CrabLang](https://crablang.org), but reserve the right to steal their logo if neccessary_

<br>

This guide is built with [mdBook](https://rust-lang.github.io/mdBook/), [a custom fork of mdBook-quiz](https://github.com/couscousdude/mdbook-quiz), and [mdBook-alerts](https://github.com/lambdalisue/rs-mdbook-alerts).  
To get started, ensure you have the latest version of Rust installed and then run:

```bash
cargo install mdbook
cargo install mdbook-alerts
```

You will then need to install the [fork of mdbook-quiz](https://github.com/couscousdude/mdbook-quiz#installation). This fork has the retry feature disabled to prevent cheating.

> [!WARNING]
> Installing this fork will overwrite the original `mdbook-quiz` installation on your machine, if you have one. You should reinstall it after you are done building this book, to prevent future conflicts.

You can start a development server with:

```bash
mdbook serve
```

These will likely be refactored into scripts in the future.  
Right now, we ain't got that kind of time.
