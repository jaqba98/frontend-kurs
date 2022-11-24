# Lekcja 6 - Układ w HTML5 oraz publikacja strony na serwisie GitHub

## 1. Układ w HTML5

### 1.1. Tradycyjne układy HTML
Utworzyć prostą stronę www opartą o znaczniki <div>. Strona ta powinna zawierać sekcję takie jak:
--------------------------------------------------------------------------------------
- Nagłówek <div id="header">
	- Logo hgroup <div id="logo">
	- Nawigacja <div id="nav">
- Sekcja o nas <div id="about-us">
- Sekcja aktualności <div id="news">
	- Artykuł 1 <div class="article">
	- Artykuł 2 <div class="article">
	- Artykuł 3 <div class="article">
	- Aside starsze aktualności <div class="older-news">
- Sekcja galeria <div id="gallery">
- Sekcja kontakt <div id="contact">
- Stopka <div id="footer">
--------------------------------------------------------------------------------------

### 1.2. Nowe elementy HTML5 służące do tworzenia układów stron
Utworzyć prostą stronę www opartą o znaczniki semantyczne. Strona ta powinna zawierać sekcję takie jak:
--------------------------------------------------------------------------------------
- Nagłówek <header>
	- Logo hgroup <hgroup id="logo">
	- Nawigacja <nav>
- Sekcja o nas <section id="about-us">
- Sekcja aktualności <section id="news">
	- Artykuł 1 <article>
	- Artykuł 2 <article>
	- Artykuł 3 <article>
	- Aside starsze aktualności <aside class="older-news">
- Sekcja galeria <section id="gallery">
- Sekcja kontakt <section id="contact">
- Stopka <footer>
--------------------------------------------------------------------------------------

### 1.3. Nagłówki <header> i stopki <footer>
--------------------------------------------------------------------------------------
Nagłówek <header> używamy do prezentowania głównego nagłówka na górze strony lub
nagłówków poszczególnych elementów <article> oraz <section>.

Stopkę <footer> używamy do prezentowania głównej stopki na dole strony lub
stopki poszczególnych elementów <article> oraz <section>.
--------------------------------------------------------------------------------------

### 1.4. Nawigacja <nav>
--------------------------------------------------------------------------------------
Element <nav> jest przeznaczony do umieszczania głównych bloków nawigacyjnych.
--------------------------------------------------------------------------------------

### 1.5. Sekcje <section>
--------------------------------------------------------------------------------------
Element <section> służy do grupowania ze sobą powiązanych elementów tworzące jedną spójną całość.
--------------------------------------------------------------------------------------

### 1.6. Artykuły <article>
--------------------------------------------------------------------------------------
Element <article> reprezentuje sekcję treści, która stanowi niezależną część dokumentu np.: artykuł w gazecie, wpis itp.
--------------------------------------------------------------------------------------

### 1.7 Sekcje boczne <aside>
--------------------------------------------------------------------------------------
Element <aside> zawiera elementy nie mające bezpośredniego związku z główna treścią strony.
Umieszczamy tam: reklamy,boczna nawigacja, cytaty itp.
--------------------------------------------------------------------------------------

### 1.8. Grupy nagłówków <hgroup>
--------------------------------------------------------------------------------------
Element <hgroup> używany jest do grupowania wielu nagłówków, aby był traktowany jako jeden nagłówek np.:
tytuł <h1> z podtytułem <h2>.
--------------------------------------------------------------------------------------

### 1.9. Ilustracje <figure> oraz <figcaption>
--------------------------------------------------------------------------------------
Element <figure> używamy, aby oznaczyć zdjęcie jakimś opisem a w <figcaption> umieszczamy ten opis.
--------------------------------------------------------------------------------------

### 1.10. Grupowanie elementów w sekcje
--------------------------------------------------------------------------------------
Wszędzie tam, gdzie nie nadają się nowe znaczniki semantyczne, trzeba użyć znacznika <div>.
Przykładem może być kontener na całą stronę www.
--------------------------------------------------------------------------------------

### 1.11. Ułatwianie starszym przeglądarkom zrozumienie nowego kodu
Aby to zrobić, trzeba dodać style CSS i dla każdego znacznika semantycznego ustawić style display: block, aby
z elementów wewnątrzwierszowych zrobić blokowy.

## 2. Publikacja strony na serwisie GitHub

### 2.1. Założenie konta na serwisie GitHub

### 2.2. Utworzenie nowego repozytorium git na serwisie GitHub

### 2.3. Wrzucenie plików na serwer

### 2.4. W zakładce settings > pages > wskazać bruncha na main

### 2.5. Zobaczyć rezultat w przeglądarce