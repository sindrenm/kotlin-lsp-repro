# Repro: Gradle import fails under Isolated Projects

Simple Gradle 9.7.1 + Kotlin project with

- Gradle Isolated Projects enabled
- A Gradle included build

kotlin-lsp `263.4421.0` fails to import this project. Flip any of the two conditions above, and it works.
