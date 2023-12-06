Adam Kwiatkowski 06/12/2023

Folder zawiera pierwszy projekt zaliczeniowy z przedmiotu techniki WWW.

Jest to to prosta strona statyczna, wykonana w układzie Grid z uwzględnieniem
wymaganej responsywności.

HTML:
Pliki Html zawierają szkielet strony: część odpowiedzialną za nawigację, kontenery, formularz kontaktowy,
Sekcje z informacjami, oraz quiz.

CSS:
Plik Css. Stosuję zmienne w celu zwiększenia czytelności kodu, ta część zapewnia również układ grid,
animacje i wyświetlanie tekstu po najechanu kursorem na jedno ze zdjęć.
Pewna część kodu nie jest wykorzystywana, ale zdecydowałem się ją zostawić, gdybym kiedyś chciał zmienić wygląda strony.

JS:
Plik script.js odpowiada za obsługę quizu: w tym celu posługuję sie id potrzebnych elementów, pytania są pobierane z pliku json przy
użyciu fetch API, użytkownik otrzymuję informację zwrotną za pomocą alertów.

Plik emailForm.js odpowiada za obsługę wysyłania wiadomości, używam tutaj usługi EmailJS, która pozwala na darmowe wysłanie do 200 maili.

JSON:
Zawiera pytania i odpowiedzi do quizu.


