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
