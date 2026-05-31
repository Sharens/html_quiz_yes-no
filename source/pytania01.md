* Czy wzorzec pyłek bazuje na tym, że klienci samodzielnie tworzą obiekty-pyłki? 
	* NIE
* Czy typowa implementacja wzorca singleton używa publicznego konstruktora? 
	* NIE
* Czy testowanie metodą czarnej skrzynki używa wyłącznie interfejsu lub programu klienckiego? 
	* TAK
* Czy klasa posiadająca wyłącznie prywatne konstruktory ogranicza tym samym możliwość własnego dziedziczenia? 
	* TAK
* Czy dobra nazwa powinna dać się wypowiedzieć? "
	* TAK
* Czy "błąd blokujący" to błąd, który zdarza się w programowaniu współbieżnym i polega na trwałym zablokowaniu dostępu do obiektu?" 
	* TAK
* Czy metody powinny mieć możliwie dużo parametrów aby w ten sposób minimalizować liczbę pól klasy? 
	* NIE
* Czy wadą wzorca strategia jest zwiększenie ilości niezbędnych klas? 
	* TAK
* Czy komentarze zawierające informacje prawne są uznawane za użyteczne? 
	* TAK
* Czy należy stosować komentarze do oznaczania miejsc w kodzie źródłowym? 
	* NIE
* Czy użycie wzorca singleton wiąże się ze złamaniem zasady pojedynczej odpowiedzialności?
	* TAK
* Czy scenariusz to ścieżka prowadząca przez przypadek użycia? 
	* TAK
* Czy wzorzec adapter pozwala zaadaptować każdą klasę do każdego potrzebnego nam interfejsu? 
	* NIE
* Czy mając do wyboru sygnalizowanie problemu przez kod powrotu i wyjątek, należy wybrać kod powrotu? 
	* NIE
* Czy jeśli działanie obiektu ma zależeć od stanu, w którym się znajduje, to warto do implementacji użyć wzorca stan? 
	* TAK
* Czy częste deklarowane metod jako metod statycznych powinno być unikane, bo blokuje możliwość użycia polimorfizmu?
	* TAK
* Czy jeśli klasa A jest składową klasy B to mamy do czynienia z kompozycją? 
	* TAK
* Czy wzorzec obserwator sprawdza się tylko wtedy, gdy jeden obiekt ma mieć jednego obserwatora?
	* NIE
* Czy zbliżający się termin wydania aplikacji jest czynnikiem, który powinien zdecydować o wykonaniu refaktoryzacji?
	* NIE
* Czy stosowanie argumentów wyjściowych jest zalecane?
	* NIE
* Czy wzorzec JavaBeans idealnie nadaje się do stworzenia klasy niezmiennej?
	* NIE
* Czy rozwiązaniem problemu zazdrości o kod jest migracja metody?
	* TAK
* Czy podstawą działania wzorca łańcuch zobowiązań jest istnienie jawnego odbiorcy żądania?
	* NIE
* Czy zamknięcie powtarzającego się kodu w osobnej klasie to także hermetyzacja?
	* TAK
* Czy metoda zaczepowa to metoda mająca pustą albo domyślną implementację?
	* TAK
* Czy wzorzec singleton jest obiektowym zamiennikiem zmiennej globalnej?
	* TAK
* Czy tworząc aplikację należy ograniczyć jej działanie wyłącznie do wymagań, które podał klient? 
	* NIE
* Czy zmienne lokalne powinny być wykorzystywane w możliwie najszerszym zakresie pionowym kodu?
	* NIE
* Czy "boska klasa" to klasa, która praktycznie nie nie robi (ma bardzo ubogi interfejs)?
	* NIE
* Czy pisząc program obsługujący grafikę wektorową warto rozważyć zastosowanie wzorca kompozyt?
	* TAK
* Czy "zasada najmniejszego zaskoczenia" oznacza, że metody powinny być implementowane tak, aby realizować oczywiste działania?
	* TAK
* Czy wzorzec strategia upraszcza testowanie kodu?
	* TAK
* Czy zasada YAGNI prowadzi do usuwania nieużywanego kodu?
	* TAK
* Czy mając wybór pomiędzy kompozycją a dziedziczeniem należy zawsze wybierać dziedziczenie? 
	* NIE
* Czy wzorzec łańcuch zobowiązań służy do silnego związania nadawcy żądania z konkretnym obiektem, który je zrealizuje?
	* NIE
* Czy testy regresyjne mają ustalić czy zmiana kodu nie zaszkodziła istniejącym funkcjonalnościom? 
	* TAK
* Czy zasada odwrócenia zależności polega na tym, że zarówno moduły wysokopoziomowe jaki i niskopoziomowe powinny zależeć od konkretnych klas?
	* NIE
* Czy optymalizacja kodu jest tożsama z jego refaktoryzacją?
	* NIE
* Czy wzorzec odwiedzający pozwala na odseparowane algorytmu od struktury obiektów?
	* TAK
* Czy symptomem antywzorca "odkrywanie koła na nowo" jest replikacja funkcji oprogramowania komercyjnego?" 
	* TAK
* Czy adapter obiektowy jest związany kontraktem klasy adaptowanej?
	* NIE
* Czy użycie wzorca singleton utrudnia testowanie aplikacji?
	* TAK
* Czy algorytm jest wzorcem projektowym?
	* NIE
* Czy wymuszanie użycia nieprzydatnej w budowanej aplikacji biblioteki może świadczyć o antywzorcu "kotwica?
	* TAK
* Czy zasada segregacji interfejsów zwiększa szansę na ponowne użycie kodu?
	* TAK
* Czy wzorzec dekorator wywołuje problemy z identycznością obiektów?
	* TAK
* Czy interfejs stosowany w implementacji wzorca kompozyt jest minimalizowany (ma zawierać wyłącznie metody pozwalające na zmianę struktury kompozytu)?
	* NIE
* Czy wzorzec fasada umożliwia wprowadzenie podziału na warstwy?
	* TAK
* Czy "ukryte sprzężenie czasowe" to problem polegający na istnieniu metod, które muszą być wykonywane w określonej kolejności, której jednak nic nie wymusza?
	* TAK
* Czy prawo Demeter to inaczej zasada maksymalnej wiedzy (żądanie, aby klasa użytkownika wiedziała możliwie dużo o klasie, z której korzysta)?
	* NIE
* Czy kod typu "wrak pociągu" narusza prawo Demeter?
	* TAK
* Czy kompozycja jest relacją na zasadzie generalizacja — specjalizacja?
	* NIE
* Czy wzorzec budowniczy standaryzuje sposób pobrania obiektu-produktu?
	* NIE
* Czy dobrą praktyką jest podawanie jako typu zmiennych nazw konkretnych klas, które będą użyte?
	* NIE
* Czy każda klasa może być użyta zgodnie z ideą wzorca prototyp?
	* NIE
* Czy gdy pomimo wielu poprawek, ten sam błąd pojawia się ponownie w aplikacji, można przypuszczać, że mamy do czynienia z antywzorcem "programowanie metodą kopiuj-wklej"?
	* TAK
* Czy dziedziczenie narusza zasady kapsułkowania?
	* TAK
* Czy antywzorzec "złoty młotek" ma miejsce wtedy, gdy różne aplikacje budowane są przez zespół za pomocą tego samego zestawu narzędzi?"
	* TAK
* Czy zasada DRY (Don't Repeat Yourself) sprowadza się do tego, aby nie używać wielokrotnie tej samej wersji biblioteki, lecz zawsze stosować ją w jej najnowszej wersji?
	* NIE
* Czy chcąc sprawdzić ile razy wykonane były metody pewnej klasy należy użyć wzorca pełnomocnik w wersji ochraniający?
	* NIE
* Czy we wzorcu pyłek tzw. "stan zewnętrzny" zapisywany jest w pyłku?
	* NIE
* Czy kompozycja to otwarte, powtórne wykorzystanie kodu?
	* NIE
* Czy klasy powinny być rozbudowywane przede wszystkim poprzez modyfikację kodu, który istnieje?
	* NIE
* Czy wzorzec fasada definiuje wzorzec wyższego poziomu, który umożliwia oddzielenie klienta od złożonego podsystemu?
	* TAK
* Czy adapter klasowy działa dla podklas adaptowanej klasy?
	* NIE
* Czy zasada jednej odpowiedzialności powoduje, że rozmiar klasy rośnie?
	* NIE
* Czy analiza tekstowa przypadku użycia wykonywana jest w celu odnalezienia kandydatów na pola klasy?
	* NIE
* Czy szczęśliwa ścieżka scenariusza przedstawia przebieg operacji, w którym nie pojawiają się problemy?
	* TAK
* Czy ścisłe przestrzeganie prawa Demeter może spowodować spadek wydajności?
	* TAK
* Czy elastyczny kod aplikacji jest elementem bezpośrednio istotnym dla jej użytkownika?
	* NIE
* Czy powinno blokować się wszystkie ostrzeżenia generowane przez kompilator, bo mogą one niepotrzebnie niepokoić użytkowników kodu?
	* NIE
