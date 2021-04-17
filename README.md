# Mülakat Kitabı

Burası [Mülakat Kitabı](https://mulakatkitabi.com)'nın mdbook reposudur. Servis edilmeye hazır dosyaları `/docs` dizininde görebilirsiniz.

# Notlar

- Yerel makinede test etmek için:

      mdbook serve -d docs/

- Daha sonra tarayıcınızdan şu adrese gidin:

      http://localhost:3000/

- `docs/` dizinini ve commitini hazırlayın:

      rm -rf docs/ && mdbook build -d docs/ && echo -n "mulakatkitabi.com" > docs/CNAME && git add docs/ && git commit -m "generate docs"

- mdbook yazılımını macOS işletim sisteminde şu şekilde yükleyebilirsiniz:

      brew install mdbook

# Lisans
MIT License. Yazı tiplerinin lisansları için kendi dizinlerine bakınız.

# Yazar
Kıvanç Yazan <kyzn at cpan dot org>
