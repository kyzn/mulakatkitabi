# Mülakat Kitabı

Burası [Mülakat Kitabı](https://mulakatkitabi.com)'nın mdbook reposudur. Servis edilmeye hazır dosyaları `/docs` dizininde görebilirsiniz.

# Notlar

- Yerel makinede test etmek için:

      mdbook serve

- Daha sonra tarayıcınızdan şu adrese gidin:

      http://localhost:3000/

- `docs/` dizinini ve commitini hazırlayın:

      rm -rf docs/ && mdbook build -d docs/ && git add docs/ && git commit -m "generate docs"

- mdbook yazılımını macOS işletim sisteminde şu şekilde yükleyebilirsiniz:

      brew install mdbook

# Lisans

- İçerikler [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.tr) ile lisanslanmıştır.
- İçeriklerin sunulmasında kullanılan [mdBook](https://github.com/rust-lang/mdBook) yazılımı [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/) ile lisanslıdır.
  - Ayrıca çeşitli yazıtiplerinin lisanslarını GitHub reposunun ilgili dizinlerinde görebilirsiniz.

# Yazar
Kıvanç Yazan <kyzn at cpan dot org>
