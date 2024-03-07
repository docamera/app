# [app.docamera.com - web interface](http://app.docamera.com)


system powiadamiania o zdarzeniach w CCTV w bezpieczny i selektywny sposób
Proste narzedzie, podajesz URL streama i system uczy się tła i obiektów i zjawisk zachodzących 
a w momencie gdy coś się dzieje to kolekcjonuje te dane i potem uczy się od osoby zarzadzajacej co ma być rozpoznane jako zagrożenie

+ czy firmy ochroniarskie potrzebują aż tak zaawansowanego rozwiązania?


+ Oni chyba już dzisiaj mają w monitoringu detekcję ruchu itp. Jak coś się dzieje, to ochroniarz z kantorku widzi na monitorze i idzie sprawdzić.
Mówimy tutaj o zastępowaniu ochroniarzy dronami i psami wypuszczanymi z klatek automatycznie na placach otwartych
 
+ Po co stale uczyć ten system? Przecież tam musisz identyfikować tylko kilka obiektów - kot, człowiek, ptak itp.
to ma być coś co będzie w stanie zrobić detekcję np. niszczenia mienia, podczas spaceru wielu ludzi
czyli ma być nie wrażliwe na sam fakt wykrycia obiektu a być wrażliwe na coś co jest uznane za czynność zakazaną, np obskianie muru


## jak to działa?

użytkownik otwiera aplikację komunikatora
łaczy się z Asystentem DoCamera
Mówi podczas video rozmowy, że chce zobaczyć kamerę:
na parking, 
przy bramie
przy wejściu do budynku
a następnie mówi, żeby pokazał mu co się wydarzyło wczoraj 
i na wyświetlaczu pokazują się kolejne zdarzenia i obiekty:
w nocy wjazd samochodu przez bramę
Parkuje na parkingu
osoba która wchodzi do budynku


user opens messenger application
connects to the DoCamera Assistant
He says during the video call that he wants to see the camera:
on parking,
at the gate
at the entrance to the building
and then tells him to show him what happened yesterday
and subsequent events and objects appear on the display:
at night, car entry through the gate
He parks in the parking lot
a person who enters a building



## rozwiazanie

 przykładowa struktura menu systemu:

+ lista użytkowników
  + prawa dostępu do
    + listy
    + akcje    
+ lista kamer
  + rozpoznane
  + przydzielone
  + konfiguracja 
+ lista objektów
  + typy obiektów: samochód, człowiek, zwierzę, robot, obiekty niezidentyfikowane, zjawiska przyrody
  + rozpoznanane
  + nierozpoznane
+ lista zachowań
  + typy zachowań: opis ruchu, opis zmian, ramy czasowe, szybkość
  + rozpoznanane
  + nierozpoznane
+ lista projektów/korelacji
  + obiekt + zachowanie
  + historia, datownik
  + trakcja, czasy i kamery oraz opis słowny kierunku zmian
