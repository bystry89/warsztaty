
# Metody NLP w badaniach nad orzecznictwem

To repozytorium zawiera materiały do warsztatów na temat zastosowania metod NLP w badaniach nad orzecznictwem.

## Przygotowanie

Aby wziąć aktywny udział w warsztatach, potrzebujesz konta Google i dostępu do Google Colab.

1. **Utwórz nowy notatnik w Google Colab**:
   - Zaloguj się na swoje konto Google.
   - Przejdź do [Google Drive](https://drive.google.com/).
   - Kliknij "Nowy" > "Więcej" > "Google Colaboratory".
     - Jeśli nie widzisz opcji "Google Colaboratory", kliknij "Połącz więcej aplikacji", wyszukaj 'Colaboratory' i zainstaluj ją, po czym kliknij "Nowy" > "Więcej" > "Google Colaboratory"

2. **Zamontuj swój Google Drive w środowisku Colab**:
   - Wklej poniższy kod do pierwszej komórki notatnika, po czym wciśnij Shift+Enter (albo znaczek Play obok komórki):

     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

   - Po paru sekundach wyświetli się okno, pytające, czy chcesz połączyć się z Google Drive. Postępuj zgodnie z instrukcjami, aby połączyć swoje Google Drive z Colab. W szczególności, udziel zgody na udzielenie wszystkich uprawnień.

3. **Ściągnij materiały na warsztaty**:
   - Wklej poniższy kod do drugiej komórki notatnika (eśli nie ma jeszcze drugiej komórki, to utwórz ją klikając na "+ Code"):

     ```python
     !wget "https://www.dropbox.com/scl/fo/kiime47h1kswj1rzj8ekv/AMkVh3-cttiE4zG8RMOue14?rlkey=zdm29ib2p9s33hch8q5hxati2&st=9g2480ir&dl=1" -O "/content/drive/My Drive/warsztaty.zip"
     !unzip "/content/drive/My Drive/warsztaty.zip" -d "/content/drive/My Drive/warsztaty"
     !rm "/content/drive/My Drive/warsztaty.zip"
     ```

   - Uruchom komórkę (Shift + Enter lub ikona "Play" obok komórki).
   - Ściągniecie materiałów zajmie parę minut.
   - Po wykonaniu komórki, idź do drive.google.com, kliknij na "Mój dysk" i wejdź w folder "Warsztaty". W folderze powinny się znajdować trzy pliki i jeden podfolder.

4. **Otwórz notatnik na Warsztaty cz. 1**:
   - W folderze "Warsztaty" kliknij dwa razy na plik "warsztaty_1.ipynb"
   - Gotowe!
