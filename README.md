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


User opens messenger app and connects to DoCamera Assistant.
During the video call, user requests camera views: parking, gate, building entrance.
User asks to see yesterday's events; display shows car entry at night.
Car parks after passing through the gate; a person enters the building.
DoCamera displays subsequent events following yesterday's incident.
Seamless integration with live video feed and historical playback.
User interacts intuitively with the DoCamera Assistant for specific views.
Real-time monitoring of key locations such as parking, gate, and building entrance.
Effortlessly review past footage and current happenings through DoCamera.
Clear visualization of events unfolding in chronological order.
Enhanced security features for comprehensive surveillance needs.
User-friendly interface for managing surveillance preferences.
Detailed insights provided through DoCamera's advanced monitoring capabilities.
Seamless transition from live video to historical footage on demand.
Flexible viewing options for tracking events over different time frames.
DoCamera's smart display showcases critical moments from the past and present smoothly.
Precise event timeline presented with location-specific details by DoCamera.
Efficient navigation through past and present visuals on the DoCamera platform.
Comprehensive coverage of events at key locations via DoCamera's intuitive controls.
Intelligent playback capabilities allow users to explore specific incidents easily.
DoCamera Assistant simplifies monitoring tasks with its interactive features.
Seamless access to surveillance feeds across key areas facilitated by DoCamera.
Visual representation of activities unfolding across specified premises via DoCamera's interface.
User enjoys a streamlined experience navigating surveillance feeds with DoCamera.


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
