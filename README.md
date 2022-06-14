Сборник статей о трансфем-переходе на русском. В разработке.

Стараемся писать доступным человеческим языком, основываемся на научных данных. Основные источники — WPATH и Transfemscience. Пока что содержимое не проверялось эндокринологами, но мы хотим это как-нибудь устроить.

## Сборка

Вам понадобится [Rust] и [MDBook]:

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
cargo install mdbook
```

Теперь можно собрать книгу и открыть её:

```sh
mdbook serve --open
```

[Rust]: https://www.rust-lang.org/tools/install
[MDBook]: https://rust-lang.github.io/mdBook/guide/installation.html
