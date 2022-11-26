# Lekcja 3 - Łącza oraz obrazy

# 1) Łącza
- folder: car-rental
	- folder: our-cars
		- plik: ford-mustang.html
		- plik: bmw.html
		- plik: ferrari-f430.html
	- plik: index.html
	- about-us.html
	- our-cars.html
	- gallery.html
	- contact.html

## 1.1) Przygotowanie podstron strony internetowej wypożyczalni samochodowej

## 1.2) Tworzenie łączy
<a href="link-do-strony">treść-linku</a>
href - atrybut wskazujący gdzie link ma prowadzić

## 1.3) Łącza do innych witryn
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a>

## 1.4) Łączenie do innych stron tej samej witryny
<a href="about-us.html">O nas</a>

## 1.5) Struktura katalogów
Opisać, w jaki sposób organizować sobie strukturę katalogów w projekcie strony internetowej.

## 1.6) Względne adresy URL kontra bezwzględne adresy URL
bezwzględny: https://example.com/images/image.jpg
względny: ./images/image.jpg

## 1.7) Łączenie z adresami poczty elektronicznej
<a href="mailto:example@gmail.com">Napisz do mnie :)</a>

## 1.8) Otwieranie stron w nowym oknie przeglądarki
<a href="gallery.html" target="_blank">Galeria (otwierane w nowej karcie)</a>

## 1.9) Łącza do określonych miejsc na tej samej stronie
<a href="#about">O nas</a>
W tej samej stronie
<div id="about">...</div>

## 1.10) Łącza do konkretnych miejsc na innej stronie
<a href="about.html#about">O nas</a>
Na innej stronie
<div id="about">...</div>

# 2. Obrazy

## 2.1) Wybieranie obrazów do prezentacji w witrynie
Opisać skąd można pobrać darmowe zdjęcia na swoją stronę internetową, opowiedzieć, że każde zdjęcie ma swoją licencję
i jeśli nie mamy praw do zdjęcia to, nie możemy go użyć.
Link: https://pixabay.com/pl/

## 2.2) Przechowywanie obrazów we własnej witrynie
Opisać jak najlepiej przechowywać obrazy we własnej witrynie, czyli w osobnym katalogu

## 2.3) Dodanie obrazu
<img src="ścieżka do pliku" alt="informacja o obrazku, jeśli nie udało się go wczytać">

## 2.4) Wysokość i szerokość obrazu
<img src="..." width="szerokość" height="wysokość">

## 2.5) W którym miejscu kodu umieszczać obrazy
przed znacznikiem <p>
w środku znacznika <p> na początku
w środku znacznika <p> w środku

## 2.6) Wyrównywanie obrazów w poziomie i pionie - stary sposób
align="left|right|center|top|bottom

## 2.7) Trzy zasady tworzenia obrazów
Opisać jaki format wybrać, dla jakiego typu obrazu.
Opisać, że zdjęcie powinno mieć wymiar taki jak umieszczamy na stronie nie większy.

## 2.8) Narzędzia do edycji i zapisu obrazu
Przedstawić narzędzie paint do zmiany rozmiaru obrazka i zapis

## 2.9) Sprawdzanie obrazów w internecie
Pokazać jak wyszukiwać obrazy w internecie oraz sprawdzanie licencji

## 2.10) HTML5 - elementy figure oraz figcaption
<figure>
	<img src="ferrari-f430.jpg" width="460">
	<figcaption>
		Curabitur id lacinia sem, semper interdum lorem. Sed id ligula lorem. Aliquam pretium feugiat eros eget ultricies. Morbi in diam bibendum, bibendum est eu, pharetra dolor.
	</figcaption>
</figure>