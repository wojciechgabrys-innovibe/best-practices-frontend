# Przekazanie projektu

### Spotkanie z&nbsp;developerem

Przekazanie projektu powinno rozpocząć się od spotkania (zwykle w&nbsp;formie telekonferencji z&nbsp;współdzielonym przez projektanta ekranem), podczas którego projektant zapoznaje frontendowca ze strukturą przekazywanego projektu i&nbsp;przechodzi przez poszczególne ekrany/flowy. Naturalnie ilość informacji przekazywana podczas jednego spotkania będzie ogromna – nie wymagamy zrozumienia/zapamiętania wszystkiego.

Omawianie projektu w&nbsp;ten sposób pozwala osobie odbierającej na zapoznanie się z&nbsp;pełnym zakresem projektu i&nbsp;jego niuansami (np. powody podjęcia pewnych decyzji podczas projektowania, dlaczego część ekranów odbiega układem od reszty, etc.).

### Format

Przekazując pliki lub dostęp do projektów w&nbsp;chmurze upewnijmy się, że osoba, która je otrzymuje będzie je w&nbsp;stanie otworzyć. Dla obniżenia progu wejścia (tam gdzie to możliwe), zalecamy korzystanie z&nbsp;rozwiązań cloud-based, takich jak [Figma](https://figma.com), [Adobe XD](https://www.adobe.com/products/xd.html), [Sketch](https://www.sketch.com/), czy [Zeplin](https://zeplin.io/) lub [Invision](https://www.invisionapp.com/). Jeśli to niemożliwe, przekonwertujmy projekty do formatu, który odbierający będzie mógł otworzyć na swoich urządzeniach.

### Struktura

**Ekrany/artboardy powinny być uporządkowane.** Decyzję o&nbsp;tym czy powinny być ułożone tematycznie (np. wszystkie ekrany związane z&nbsp;profilem użytkownika ustawione blisko siebie), czy logicznie (sekwencja ekranów odpowiadająca za flow płatności) czasami zależy od specyfiki projektu i&nbsp;pozostawiamy ją projektantowi.

Decyzję o&nbsp;tym czy ekrany responsywne (mobile, tablet, desktop) powinny być ułożone obok siebie, czy być pogrupowane rozmiarami na osobnych stronach pozostawiamy projektantowi i&nbsp;zespołowi – czasami ta sama osoba wdraża je wszystkie, a&nbsp;innym razem powstają odrębne aplikacje (np. web i&nbsp;React Native), które wdrażają różne osoby (i wygodniej jest im się obracać tylko w&nbsp;ramach swoich zadań). Najważniejsza jest tu wygoda zespołu i&nbsp;konsekwencja.

Dobrym zabiegiem jest dodanie dużych nagłówków (ok. `200pt`) opisujących grupy ekranów – dzięki temu robiąc zoom out (aby zobaczyć wszystkie widoki) łatwiej odnajdujemy się w&nbsp;projekcie.

**Pamiętajmy, aby ukończone ekrany dokładnie nazywać.** Pomaga to w&nbsp;ich wyszukiwaniu i&nbsp;przeglądaniu. O&nbsp;ile w&nbsp;przypadku kilkunastu ekranów nawigowanie nawet po nieopisanych ekranach jest to łatwe, o&nbsp;tyle w&nbsp;przypadku projektów posiadających po kilkaset widoków konsekwencja w&nbsp;nazewnictwie zaprocentuje i&nbsp;ułatwi pracę wszystkim osobom zaangażowanym w&nbsp;proces tworzenia produktu.

**Projektuj nowe widoki w&nbsp;miejscu z&nbsp;dala od już gotowych.** W&nbsp;przypadku narzędzi pozwalających na kolaborację, staraj się wydzielić obszar zawierający już ukończone widoki (np. używając Pages w&nbsp;przypadku Figmy i&nbsp;Sketcha). Pozwoli to uniknąć nieporozumień które z&nbsp;ekranów są już gotowe, a&nbsp;nad którymi jeszcze trwają prace.

**Interaktywne elementy interfejsu i&nbsp;przejścia pomiędzy ekranami.** Jeśli program graficzny w&nbsp;którym przygotowujemy materiały nam na to pozwala (np. Figma, Sketch), warto poświęcić czas na zamarkowanie interakcji poszczególnych elementów interfejsu (np. kliknięcie w&nbsp;przycisk powoduje przejście do kolejnego ekranu lub pojawienie się pop up'u). Dzięki temu będziemy w&nbsp;stanie:

* Samodzielnie odkryć brakujące ścieżki użytkowników
* Dostarczyć klientowi “prototyp” aplikacji, co pozwoli mi na zweryfikowanie poprawności pierwotnych założeń i&nbsp;ewentualną szybką zmianę kursu zanim projekt trafi do wdrażania
* Dostarczyć programistom dodatkowy poziom informacji (w postaci interaktywnej dokumentacji), co zdecydowanie ułatwi im wybór.

# Style guide

Omawiając to zagadnienie mamy na myśli dedykowany page lub artboard, gdzie znajdują się podobne do siebie komponenty (np. zestaw kolorów, hierarchia nagłówków, kontrolki formularzy, etc.). Pozwala to na łatwe wychwycenie ich wspólnych właściwości (np. podobieństwo fontów, obramowań i&nbsp;paddingów wewnątrz pól tekstowych, list) i&nbsp;utrzymanie spójności w&nbsp;projekcie. Osoba wdrażająca nasze projekty będzie wiedziała jak ma wyglądać zwykły input w&nbsp;różnych stanach (pusty, z&nbsp;treścią, z&nbsp;placeholder’em, podświetlony kursorem, aktywny, zablokowany) i&nbsp;w różnych wariantach (zwykły input, input do wprowadzania kwoty w&nbsp;danej walucie, dropdown, etc.)

Dodatkowym atutem styleguide’u jest możliwość korzystania z&nbsp;niego jak z&nbsp;pudełka z&nbsp;klockami Lego – nowe ekrany tworzy się szybciej i&nbsp;pewniej (mając świadomość zachowania spójności z&nbsp;resztą projektu). W&nbsp;ekstremalnych przypadkach (np. nasza nieobecność) programista zaopatrzony w&nbsp;dobrze przygotowany style guide będzie sam w&nbsp;stanie zbudować brakujący moduł lub widok z&nbsp;posiadanych komponentów.

# Popularne elementy

Nie jesteśmy w&nbsp;stanie przewidzieć i&nbsp;opisać tutaj wszystkich wariantów elementów jakich będziemy potrzebować (przygotowujemy projekty dla różnorodnych rynków i&nbsp;odbiorców), ale z&nbsp;doświadczenia wiemy, że jest kilkanaście typów, które powtarzają się na przestrzeni różnych projektów. Potraktuj tę listę jako inspirację w&nbsp;poszukiwaniu elementów, które mogły Ci umknąć podczas projektowana.

>{must_have} **Must have** – Jeśli opisywany element da się zastosować w&nbsp;przygotowywanym projekcie, jego przygotowanie jest wymagane.

>{nice_to_have} **Nice to have** – Jeśli opisywany element da się zastosować w&nbsp;przygotowywanym projekcie, jego przygotowanie jest mile widziane.

#### Kolory

>{must_have} **Zdefiniuj paletę kolorów.** Przygotowując projekt zdefiniuj podstawową paletę kolorów (tło strony, body text, akcenty) i&nbsp;staraj się nimi operować na przestrzeni projektu. Zbyt duża liczba kolorów i&nbsp;ich odcieni może łatwo i&nbsp;szybko wprowadzić wizualny harmider.

>{must_have} **Definiuj nowe kolory zamiast zmieniać opacity.** [TODO]

>{nice_to_have} **Przygotuj zestaw kolorów dla wykresów.** [TODO]

#### Nagłówki

>{must_have} **Zaprojektuj strukturę nagłówków H1-H6.** Poza zdefiniowaniem fontu, rozmiaru i&nbsp;koloru pamiętaj również o&nbsp;takim ustawieniu line height / marginesów, aby dobrze komponowały się z&nbsp;pozostałymi nagłówkami i&nbsp;body text.

#### Formularze

>{must_have}**Kontrolki formularzy** (form elements):
> * Etykieta (Label)
> * Pole tekstowe (Input), Pole numeryczne
> * Dropdown (Select)
> * Textarea
> * File input
> * Time picker, Date picker, Date time picker
> * Suwak / Zakres (Range)
> * Button
> * Radio button
> * Checkbox / Switch
> * Opis pola (np. informacja o&nbsp;minimalnej długości hasła)
> * Komunikat błędu
> * Informację o&nbsp;obowiązku wypełnienia/możliwości pozostawienia pustym (Required/Optional)

>{nice_to_have}**Przygotowanie komponentów pól.** Poza samym zaprojektowaniem kontrolek formularzy warto zaprojektować też całe pola (np. złożone z&nbsp;etykiety, pola tesktowego i&nbsp;opisu) tak, aby były elastyczne (można było je rozciągać/zwężać) i&nbsp;zawierały zdefiniowane marginesy/odstępy.

>{nice_to_have}**Sekcje formularzy.** W&nbsp;przypadku długich/skomplikowanych formularzy, podział ich na sekcje (z nagłówkami i&nbsp;opisami) pozytywnie wpływa na szybkość i&nbsp;skuteczność ich wypełniania.

>{nice_to_have}**Układ horyzontalny.** Niektóre krótkie formularze (takie jak logowanie w&nbsp;nagłówku strony, czy zapisywanie się do newslettera) można ułożyć poziomo (pola są wtedy obok siebie).

#### Szablony e-mail

>{must_have}**Rozważ wykorzystanie gotowych szablonów email.** W&nbsp;przypadku e-maili należy mieć świadomość, że ograniczenia różnych klientów pocztowych wyświetlać je nieco inaczej (co wynika z&nbsp;ich ograniczeń) – część z&nbsp;nich radzi sobie z&nbsp;responsywnymi widokami i&nbsp;GIFami, a&nbsp;inne używają uproszczonej wersji Word’a do renderowania treści (serio!).
>
> Przed przystąpieniem do projektowania szablonów e-mail od zera warto rozważyć tylko drobne zmiany (np. kolorów) w&nbsp;szablonach wbudowanych we framework (np. w&nbsp;przypadku Laravela), skorzystanie z&nbsp;gotowych, darmowych szablonów (np. w&nbsp;[Maizzle](https://maizzle.com/), który pokochają developerzy uwielbiający Tailwind CSS) lub namówienie klienta na wydanie ok. $20 na [gotowy, komercyjny szablon](https://themeforest.net/category/marketing/email-templates).

>{must_have}**Ogólny szablon dla mailingów transakcyjnych.** Warto przygotować ogólny widok, który będzie zawierał:
> * Logo
> * Kolory tła
> * Kilka poziomów nagłówków (zwykle H1-H3 wystarczają)
> * Body text
> * Hiperłącza
> * Sposób ulokowania grafik (rozmiar, marginesy)
> * Cytat blokowy

>{must_have}**Domyślne fonty.** Jeśli nasz projekt korzysta z&nbsp;niestandardowych fontów, dla samych e-maili warto wybrać krój, który jest domyślnie dostępny.

>{must_have}**Tytuły maili.** Sam projekt graficzny i&nbsp;treść maila to nie wszystko – pamiętaj o&nbsp;przygotowaniu tytułu wiadomości.

#### Strony statyczne (bogate w&nbsp;tekst)

>{must_have} Przygotuj jeden gotowy szablon strony statycznej, którą będzie traktowana za uniwersalną (do której będziemy wlewali tekst).

>{must_have} Do tego typu stron można zaliczyć regulamin, politykę prywatności, blog czy strony pomocy. Warto przygotować ogólny widok, który będzie zawierał:
> * Nagłówki (H1-H6) ze zdefiniowanymi fontami, kolorami, wysokością wierszy i&nbsp;odstępami przed/po. Warto przygotować też wariant obrazujący wygląd gdy nagłówek jest linkiem.
> * Body text
> * Hiperłącza
> * Sposób ulokowania grafik (rozmiar, marginesy)
> * Cytat blokowy
> * Listy (uporządkowane i&nbsp;nieuporządkowane)
> * Podczas projektowania warto pamiętać o&nbsp;przygotowaniu wariantów responsywnych (w zależności od potrzeb i&nbsp;wytycznych projektu)
> * Korzystanie z&nbsp;gotowych stylów dostępnych w&nbsp;bibliotekach (Bootstrap, Tailwind CSS)

#### Strony z&nbsp;uwierzytelnianiem

>{must_have} Do tego typu stron można zaliczyć:
> * Rejestrację nowego konta
> * Rejestrację z&nbsp;zaproszenia innego użytkownika (w celu dołączenia do konta firmowego)
> * Logowanie + wersja dla włączonego uwierzytelniania dwuskładnikowego (2FA)
> * Resetowanie hasła
> * Usuwanie konta

#### Onboarding

>{nice_to_have} **Omów z&nbsp;klientem/PMem potrzebę przygotowania procesu onboardingu.** Istniejący i&nbsp;dobrze przygotowany proces onboardingu to często kluczowy element, który decyduje o&nbsp;tym czy użytkownik będzie korzystał z&nbsp;aplikacji, czy ją porzuci.

>{nice_to_have} **Zdefiniuj cele onboardingu.** Cele, które będą chcieli osiągnąć stakeholderzy, będą się różniły w&nbsp;różnych aplikacjach. Skomplikowane aplikacje powinny prowadzić użytkownika za rękę pokazując mu kolejne funkcje, wykorzystać kreatory do wypełnienia pustego workspace’a danymi, etc. (Facebook stawia sobie za cel dodanie 4 osób do znajomych w&nbsp;ciągu pierwszych 20 dni od założenia konta; Slack chce, aby wewnątrz firmy wysłano co najmniej 5000 wiadomości).

#### Happy path i&nbsp;unhappy path

>{must_have} Projektując ścieżki użytkowników warto zastanowić się co powinno się wydarzyć (i jak powinny wyglądać ekrany), gdy dana akcja się nie powiedzie (np. nie udało się zapisać do newslettera ponieważ e-mail jest niepoprawny, lub znajduje się już na naszej liście).

#### Strony błędów

>{nice_to_have} **Zrozumiałe komunikaty.** O&nbsp;ile Błąd 404 przeszedł już do popkultury, tak inne kody błędów (403: Brak uprawnień (Forbidden), lub 500: Błąd serwera (Internal server error) są niezrozumiałe dla większości użytkowników.

>{nice_to_have} **Nie pozostawiaj użytkownika samego.** Poza opisaniem problemu w&nbsp;sposób zrozumiały dla wszystkich warto jest dać użytkownikom możliwość kontynuowania (np. “Przejdź do strony głównej”, “Napisz do nas na support@companyname.com, żebyśmy mogli Ci pomóc”) zamiast pozostawiania ich w&nbsp;ślepym zaułku.


### Dodatkowe materiały

Poza samymi plikami graficznymi, na projekty składają się również:

#### Zdjęcia i&nbsp;ilustracje

>{must_have} **Licencje i&nbsp;prawa do wykorzystania.** Upewnijmy się, że posiadamy należyte licencje, które pozwalają nam na korzystanie z&nbsp;nich w&nbsp;danym polu eksploatacji.

>{must_have} **Poza osadzeniem takiej grafiki w&nbsp;projekcie przekazujmy je również jako osobne pliki.** Jeśli na grafiki w&nbsp;projekcie nakładaliśmy filtry lub efekty, to reprodukujemy je na plikach w&nbsp;wysokiej rozdzielczości i&nbsp;dopiero w&nbsp;takiej formie eksportujemy a&nbsp;następnie przekazujemy.

>{must_have} **Zdjęcia i&nbsp;ilustracje przekazujemy nieprzycięte, w&nbsp;maksymalnie wysokiej rozdzielczości.** Ułatwi to osobie je wdrażającej ich dopasowanie do różnych formatów, rozdzielczości i&nbsp;gęstości (pikseli) ekranów.

>{must_have} **Nie oszczędzamy na wadze plików. Na koniec lepiej kompresować niż denerwować się na niską jakość.** Na koniec lepiej kompresować niż denerwować się na niską jakość.

>{must_have} **Formaty eksportu grafik.**
> * Zdjęcia przekazujemy jako JPEG (z najmniejszą możliwą kompresją)
> * Ilustracje wektorowe i&nbsp;ikony przekazujemy jako SVG lub ewentualnie EPS,
> * Grafiki rastrowe przekazujemy jako PNG 24bit non-interlaced (bez przeplotu) z&nbsp;włączonym transparency (przezroczystość/kanał alpha).
> * Eksportując grafiki do docelowych rozmiarów warto zastanowić się nad nowożytnymi formatami kompresji: WEBP, HEIC/HEIF, AVIF, APNG (tam gdzie da się je zastosować)

#### Logotypy

>{must_have} **Przekazujemy wszystkie warianty w&nbsp;popularnych formatach.** Jeśli otrzymaliśmy logotypy od klienta, upewnijmy się, że są one w&nbsp;formatach z&nbsp;którymi poradzi sobie frontendowiec (łatwiej poradzić sobie z&nbsp;SVG lub EPS niż z&nbsp;AI).

>{nice_to_have} **Przekaż księgę znaku.** Jeśli posiadamy księgę znaku lub brandbook (które zwykle zawierają informacje o&nbsp;kolorach, obszarach ochronnych i&nbsp;przykłady poprawnego/błędnego użycia) – przekażmy je razem z&nbsp;logotypami.

#### Fonty

>{must_have}
> * Upewnijmy się, że posiadamy należyte licencje, które pozwalają nam na korzystanie z&nbsp;nich w&nbsp;danym polu eksploatacji.
> * Jeśli licencja lub koszty nie pozwalają nam na wykorzystanie danej rodziny czy kroju w&nbsp;projekcie, poszukajmy darmowego lub tańszego zamiennika na Google Fonts, Font Squirrel, czy Adobe Typekit (płatny)
> * W&nbsp;przypadku problematycznych/egzotycznych formatów plików możemy spróbować dokonać konwersji (o ile pozwala nam na to licencja)
> * W&nbsp;przypadku projektów dla www starajmy się ograniczyć liczbę rodzin i&nbsp;krojów na poszczególnych stronach – poprawi to czytelność i&nbsp;zredukuje rozmiar strony (co przełoży się na szybkość jej ładowania i&nbsp;wyniki w&nbsp;Lighthouse).
> * Jeśli to możliwe ograniczajmy charsety (np. jeśli planujemy użyć jakiś specjalny font monospaced do wyświetlania danych numerycznych, nie będziemy potrzebowali glyphów z&nbsp;cyrylicy)

#### Ikony

>{nice_to_have} Przygotowując projekt www zadbajmy o&nbsp;faviconę (w dobie rosnących rozdzielczości i&nbsp;[szybko rozwijających się przeglądarek](https://caniuse.com/link-icon-svg) warto zastanowić się nad użyciem SVG) i&nbsp;zestaw ikon (w odpowiednich rozmiarach) dla aplikacji PWA. [Zbiór dokładnych informacji](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs).
>
> Jeśli w&nbsp;projekcie korzystamy z&nbsp;gotowego zestawu ikon, oprócz jego przekazania (np. w&nbsp;formie paczki plików lub linku do biblioteki dostępnej online) warto nazwać komponenty zawierające ikony tak jak nazwy plików (lub dodawać te nazwy w&nbsp;formie komentarzy) – ogromnie ułatwia to znajdowanie i&nbsp;osadzanie poprawnych ikon.

#### Social media

Nawet jeśli klient nie planuje obecności w&nbsp;mediach społecznościowych (w celach stricte marketingowych), niektóre platformy wymagają założenia kont w&nbsp;celu integracji z&nbsp;ich API. W&nbsp;przypadku produktów

>{nice_to_have}**Open Graph Images.** Większość sieci społecznościowych i&nbsp;komunikatorów wyświetla metadane i&nbsp;miniaturę po wklejeniu linku – z&nbsp;tego powodu warto przygotować dedykowane grafiki dla poszczególnych platform (np. Facebook, Twitter). Nie podajemy konkretnych rozdzielczości i&nbsp;formatów, bo te ulegają ciągłym zmianom. Niektóre formaty wymagają odpowiedniego przemyślenia i&nbsp;zaprojektowania, ponieważ ta sama grafika jest przycinana na różne sposoby i&nbsp;wyświetlana na różnych urządzeniach (desktop/mobile).
> * [https://www.bannerbear.com/](https://www.bannerbear.com/)

>{nice_to_have}**Avatary.** Część platform społecznościowych operuje avatarami w&nbsp;kształcie kwadratu (zwykle z&nbsp;zaokrąglonymi narożnikami), a&nbsp;część przycina je do kształtu koła. Jeśli niemożliwym jest przygotowanie uniwersalnego obrazka lepiej przygotować dwa osobne. Roździelczość 1024x1024 powinna być wystarczająca. Eksportuj je w&nbsp;formie kwadratu, bez przezroczystości (nawet te okrągłe – platformy i&nbsp;aplikacje zawsze same maskują). Dzięki temu nie będzie problemu gdy okrągły avatar (np. z&nbsp;Twittera) zostanie później zamaskowany z&nbsp;użyciem tzw. [Squircle](https://en.wikipedia.org/wiki/Squircle) (jak to miało ostatnio miejsce w&nbsp;Clubhouse, które importowało avatary z&nbsp;Twittera).

#### Pozostałe
>{nice_to_have} Jeśli wiemy, że przygotowywana strona będzie korzystała z&nbsp;dobrodziejstw PWA, warto przygotować [splash screen](https://love2dev.com/pwa/splash-screen/) i&nbsp;[ikony aplikacji](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs).
