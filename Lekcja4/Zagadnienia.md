# Lekcja 4 - Tabele i Formularze

## 1. Tabele

### 1.1. Czym jest tabela?
Tabela prezentuje informacje zapisane w układzie siatki. Składa się z wierszy oraz kolumn.

### 1.2. Podstawowa struktura tabel
<table> - główny element tworzący tabelę
<tr> - początek nowego wiersza tabeli - table row
<td> - początek komórki tabeli - table data

### 1.3. Nagłówki tabel
<th> - nagłówek kolumny lub wiersza - table heading

### 1.4. Łączenie komórek z sąsiadujących kolumn
...
<tr>
	<td>1</td>
	<td colspan="2">2</td>
	<td>3</td>
</tr>
<tr>
	<td>4</td>
	<td>5</td>
	<td>6</td>
	<td>7</td>
</tr>
...

### 1.5. Łączenie komórek w sąsiadujących wierszach
...
<tr>
	<td>1</td>
	<td rowspan="2">2</td>
	<td>3</td>
</tr>
<tr>
	<td>4</td>
	<td>5</td>
</tr>
...

### 1.6. Długie tabele
<thead> - nagłówki tabeli
<tbody> - główna zawartość tabeli
<tfoot> - stopka tabeli

## 2. Formularze

### 2.1. Dlaczego formularze?
Opisać czym są formularze oraz po co umieszcza się je na stronie.

### 2.2. Jak działają formularze?
Opisać jak działają formularze, czyli:
- użytkownik wypełnia formularz i wciska przycisk, by przesłać dane na serwer,
- serwer otrzymuje wszystkie nazwy pól formularza wraz z ich wartościami,
- serwer przetwarza te informacje za pomocą technologii back-end, generuje nową stronę www i zwraca do przeglądarki klienta.

### 2.3. Struktura formularzy
<form action="" method="">
	...
</form>

action - Adres URL strony na serwerze, do której przekazywane są wszystkie informacje.
method - Metoda wysyłania danych get / post
get - Wartości pól dodawane są na końcu adresu URL.
post - Wartości przesyłane są w tzw. nagłówkach HTTP.

### 2.4. Pola tekstowe
<input type="text" name="login" maxlength="20">
name - Nazwa identyfikująca dane pole.
maxlength - Określenie ile maksymalnie ilości znaków może przechowywać pole.

### 2.5. Pole hasła
<input type="password" name="haslo" maxlength="20">
name - Nazwa identyfikująca dane pole.
maxlength - Określenie ile maksymalnie ilości znaków może przechowywać pole.

### 2.6. Wielowierszowe pola tekstowe
<textarea name="wiadomosc">Treść wiadomości...</textarea>
name - Nazwa identyfikująca dane pole.

### 2.7. Przyciski opcji
<input type="radio" name="game" value="gta" checked="checked"> gta
<input type="radio" name="game" value="gothic"> gothic
<input type="radio" name="game" value="minecraft"> minecraft
name - Nazwa identyfikująca dane pole.
value - Wartość, jaka zostanie przesłana na serwer.
checked="checked" - Określenie, który przycisk opcji powinien zostać domyślnie zaznaczony po załadowaniu strony.

### 2.8. Pola wyboru
<input type="checkbox" name="rule" value="true" checked="checked"> Zasady?
name - Nazwa identyfikująca dane pole.
value - Wartość, jaka zostanie przesłana na serwer.
checked="checked" - Określenie, który przycisk opcji powinien zostać domyślnie zaznaczony po załadowaniu strony.

### 2.9. Listy rozwijane
<select name="games">
	<option value="gta">gta</option>
	<option value="gothic" selected="selected">gothic</option>
	<option value="minecraft">minecraft</option>
</select>
name - Nazwa identyfikująca dane pole.
value - Wartość, jaka zostanie przesłana na serwer.
selected="selected" - Określenie, która wartość zostanie domyślnie wybrana.

### 2.10. Lista wielokrotnego wyboru
<select name="games" size="2" multiple="multiple">
	<option value="gta">gta</option>
	<option value="gothic" selected="selected">gothic</option>
	<option value="minecraft">minecraft</option>
</select>
name - Nazwa identyfikująca dane pole.
value - Wartość, jaka zostanie przesłana na serwer.
selected="selected" - Określenie, która wartość zostanie domyślnie wybrana.
size - Określa ile opcji, ma być widoczne na ekranie.
multiple="multiple" - Umożliwia użytkownikowi wybór wielu opcji [ctrl].

### 2.11. Pole przesyłania plików
<input type="file" name="plik">

### 2.12. Przycisk przesyłający
<input type="submit" value="Wyślij">
value - Określenie wartości wyświetlonej na przycisku.

### 2.13. Przyciski z obrazem
<input type="image" src="btn.png" width="150" height="150">

### 2.14. Element button oraz pola ukryte
<button>
	<img ...>
	Jakiś tekst
</button>
<input type="hidden">

### 2.15. Dodawanie etykiety do pól formularzy
<label>
	Imie: <input type="text" name="imie">
</label>

<label for="imie">Imie: </label>
<input type="text" name="imie" id="imie">

for - Określa, do którego pola formularzu należy dana etykieta.

### 2.16. Grupowanie elementów formualrzy
<fieldset>
	<legend>Logowanie<legend>
	<input type="text" name="login">
	<input type="password" name="password">
	...
</fieldset>

### 2.17. HTML5: Weryfikacja pól formularzy
required="required" - Sprawia, że dane pole formularzu jest wymagane.

### 2.18. HTML5: Pole daty
<input type="date">

### 2.19. HTML5: Pola adresów e-mail i URL
<input type="email">
<input type="url">

### 2.20. HTML5: Pola wyszukiwania
<input type="search" placeholder="Szukaj">
placeholder - Tekst prezentowany na polu tekstowym, jeśli jest puste.