# Programowanie_w_Pythonie_06_06_2022
Dataclasses


Stwórz dataclass, która będzie służyć do opisu wahadła matematycznego. Jako wartości inicjujące powinno się podać jego długość, przyspieszenie grawitacyjne, amplitudę, oraz fazę początkową (jako pole opcjonalne z wartością domyślną 0). Zakładamy, że przy fazie 0, w chwili t=0 wychylenie powinno być maksymalne (tzn. drgania opisywane są funkcją cos).
Metoda __post_init__ powinna obliczyć częstość kątową drgań własnych oraz okres i zapisać je jako pola (atrybuty). 

Klasa powinna posiadać metody zwracające w chwili t:
Wychylenie z położenia równowagi
Prędkość
Przyspieszenie
