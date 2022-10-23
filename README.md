# Bolero editor performance issue #272 repro

This repository reproduces a pathological case for Bolero 0.20 that causes the F# code service to slow down or even crash. See https://github.com/fsbolero/Bolero/issues/272

Here is the status for the IDEs I've been able to test:

| Editor                | Status |
|-----------------------|--------|
| VSCode + Ionide 7.3.1 | OK     |
| Rider 2021.3.4        | Crash  |
| Rider 2022.2.3        | OK     |
| Visual Studio 17.0.0  | Crash  |
| Visual Studio 17.3.6  | OK     |
