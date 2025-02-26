# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to
  - Wady: 
  Awaria magistrali powoduje awarię całej sieci, problemy z wydajnością, 
  trudności w diagnostyce i konserwacji, 
  ograniczona długość kabla, 
  kolizje w transmisji,
  bezpieczeństwo,
  - Zalety: 
  Prostota, 
  niski koszt, 
  elastycznosc w rozbudowie, 
  zastosowanie w malych sieciach
  - Gdzie stosowane: 
  Małe sieci lokalne (lan),
  Sieci oparte na standardzie 10BASE-2 (Thin Ethernet),
  Systemy monitoringu i czujników,
  Starsze technologie komunikacyjne,
  Sieci tymczasowe i eksperymentalne
- **Topologia pierścienia** (Ring): jest to
  - Wady: 
  Awaria jednego elementu może zniszczyć całą sieć, 
  trudności w diagnostyce i konserwacji, 
  zmniejszona wydajność w dużych sieciach, 
  trudności w dodawaniu lub usuwaniu urządzeń.
  - Zalety: 
  Prosta instalacja, 
  brak kolizji w transmisji, 
  przewidywalność przesyłania danych, 
  łatwiejsze zarządzanie przepustowością.
  - Gdzie stosowane: 
  Stare systemy sieciowe,
  Sieci o ograniczonej liczbie urządzeń,
  Sieci o dużym stopniu niezawodności,
  FDDI (Fiber Distributed Data Interface),
  Przemysłowe sieci SCADA,
  Wirtualne sieci lokalne (VLAN),
  Sieci w zastosowaniach wojskowych i rządowych
- **Topologia gwiazdy** (Star): jest to
  - Wady: 
    Awaria centralnego urządzenia może spowodować awarię całej sieci.
    Wyższe koszty okablowania i utrzymania w większych sieciach.
    Zależność od wydajności centralnego urządzenia.
  - Zalety:
    Łatwość instalacji, rozbudowy i zarządzania.
    Izolacja awarii urządzeń.
    Wysoka wydajność i brak kolizji.
    Łatwa diagnoza problemów i konserwacja.
    Elastyczność i skalowalność. 
  - Gdzie stosowane: 
  Sieci lokalne (lan),
  Sieci w domach i mieszkaniach,
  Sieci bezprzewodowe (Wi-Fi),
  Sieci w centrach danych (Data Centers),
  Sieci w szkołach i uczelniach,
  Przemysł i automatyka,
  Sieci telekomunikacyjne,
  Zastosowania w dużych biurach i korporacjach,
  Zdalne biura i filie


## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to
  - Wady: 
    Ograniczona skalowalność.
    Brak redundancji i ryzyko awarii połączenia.
    Wysokie koszty okablowania w dużych sieciach.
  - Zalety:
    Prostota konfiguracji i utrzymania.
    Wysoka wydajność i bezpieczeństwo.
    Niskie opóźnienia oraz stabilność połączenia. 
  - Zastosowanie: 
    Połączenia między odległymi biurami,
    Połączenia typu "backhaul",
    Połączenia bezpośrednie,
    Wysokowydajne połączenia w centrach danych,
    Połączenia między urządzeniami IoT (Internet of Things)  
- **Przekazywanie żetonu** (Token Passing): jest to
  - Wady: 
    Możliwość zagubienia lub uszkodzenia żetonu.
    Opóźnienia w dużych sieciach.
    Wymaga dużej synchronizacji i zaawansowanego zarządzania w przypadku awarii.
  - Zalety:
    Brak kolizji i wydajniejsze wykorzystanie medium.
    Równy dostęp do medium dla wszystkich urządzeń.
    Wysoka kontrola nad transmisją danych i lepsza synchronizacja. 
  - Zastosowanie: 
    Sieci w topologii pierścienia
    Sieci token-passing w rozproszonych systemach
    Sieci LAN
    Zastosowania w telekomunikacji i systemach transmisji danych
- **Wielodostępowa** (Multiple Access): jest to
  - Wady: 
    Kolizje
    Złożoność implementacji
    Zwiększone opóźnienia
    Potrzeba synchronizacji
  - Zalety: 
    Efektywne wykorzystanie medium transmisyjnego
    Skalowalność
    Eliminacja zakłóceń
    Równoczesne przesyłanie danych
 - Zastosowanie: 
    Sieci komórkowe
    Wi-Fi
    Sieci satelitarne
    Internet rzeczy (IoT)
