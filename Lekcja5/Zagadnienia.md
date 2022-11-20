# Lekcja 5 - Dodatkowe Elementy HTML oraz Wideo i Audio

## 1. Dodatkowe Elementy HTML

### 1.1. Ewolucja języka HTML
https://www.silverstripe.org/blog/html5-and-beyond/

### 1.2. Deklaracja DOCTYPE
https://www.w3schools.com/tags/tag_doctype.asp
<!DOCTYPE html> - Strona napisana jest w HTML5.

### 1.3. Komentarze w kodzie HTML <!-- treść komentarza -->
Po co stosujemy komentarze:
- opisać trudny kod, aby jak wrócimy do niego po długim czasie być w stanie łatwiej go zrozumieć,
- za komentować kod, który nie chcemy, aby się wyświetlał na stronie, ale również chcemy go zachować

### 1.4. Atrybuty ID oraz CLASS
Opisać wszystko na temat atrybutów id oraz class:
- są to atrybuty globalne, czyli można je dodawać do każdego typu znacznika HTML,
- atrybut id identyfikuje dany znacznik HTML (może być tylko raz na stronie),
- atrybut class identyfikuje grupę znaczników HTML (może być wiele razy na stronie).

*** !!! Pokazać na stronie MDN informacje odnośnie do globalnych atrybutów id oraz class !!! ***

### 1.5. Elementy blokowe i wewnątrzwierszowe
Opisać różnicę między elementami blokowymi oraz wewnątrzwierszowe i pokazać przykłady.

### 1.6. Grupowanie tekstu i elementów w blokach <div> i elementów wewnątrzwierszowych <span>
Element <div> pozwala na grupowanie dowolnych elementów, umieszczając je wewnątrz jednego bloku. Nie nadaje tym elementom żadnego dodatkowego znaczenia.

Element <span> odpowiednik tagu div dla elementów wewnątrzwierszowych stosowany do grupowania elementów wewnątrzwierszowych.

### 1.7. Pływające ramki <iframe>
Okno, w którym możemy wyświetlić zawartość innej strony internetowej. Zazwyczaj używa się ją do wyświetlenia mapy Google na swojej stronie internetowej.

*** !!! Pokazać jak umieścić mapę Google na swojej stronie internetowej. !!! ***

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d80600.32175279979!2d20.545601935383452!3d50.85412741271649!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47178818af891105%3A0x5025d8b8c0cdcdf3!2sKielce!5e0!3m2!1spl!2spl!4v1668953402731!5m2!1spl!2spl" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

src - adres strony internetowej, która ma być wyświetlona,
height - wysokość ramki,
width - szerokość ramki

### 1.8. Informacje o stronie <meta>
Element <meta> umieszczany jest wewnątrz elementu <head> i zawiera informacje dotyczące danej strony internetowej.
<meta name="" content="">

name - nazwa ustawianej wartości,
content - wartość

name === description - opis strony,
name === charset - ustawia kodowanie strony np.: utf-8,
name === keywords - lista oddzielona przecinkime słów kluczowych,
name === robots - określa czy wyszukiwarki powinny indeksować stronę (index, noindex, ...),
name === author - określa autora strony

### 1.9. Symbole specjalne
Istnieje duża grupa znaków specjalnych w HTML, pokazać jak je znaleźć oraz jak używać.
https://www.whatsmyip.org/html-characters/

## 2. Wideo i Audio

### 2.1. Przedstawienie formatów klipów wideo ???

### 2.2. Korzystanie z usług udostępniania wideo
Przedstawić jak wrzucić film na swoją stronę internetową korzystając z zewnętrzne usługi takie jak YouTube.
https://www.youtube.com/watch?v=qY87R2Id4mk&ab_channel=Kot

<iframe width="560" height="315" src="https://www.youtube.com/embed/qY87R2Id4mk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 2.3. Umieszczanie klipów wideo na stronach www oraz wiele źródeł materiału wideo
https://pixabay.com/pl/videos/seul-ruch-drogowy-samochody-miasto-21118/

<video> - element HTML do wstawienia filmu na stronie.
preload - informuje co zrobić po wczytaniu strony 
src -
poster - 
width, height - 
controls -
autoplay -
muted - 

<source> -

### 2.4. Stosowanie znacznika audio na stronach www oraz wiele źródeł materiału audio ???
