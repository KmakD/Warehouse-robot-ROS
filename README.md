# Warehouse-robot-ROS
Projek miał na celu stworzenie oprogramowania robota magazyniera. Oprogramowanie zostało stworzone w środowisku Matlab z wykorzystaniem dodatku ROS toolbox. Zadanie polegało na pobieraniu przesyłek z trzech punktów odbioru, a następnie przetransportowanie ich do punktów dostarczenia. Robot rozpoczyna pracę w stacji dokującej, a po wykonaniu każdego dostarczenia paczki sprawdza czy jest kolejna paczka do odbioru i z którego stanowiska ma ją odebrać. 
Wizualizacja przestrzeni pracy robota została wykonana w symulatorze Gazebo. W pierwszym etapie stworzona została mapa otoczenia (_generator_mapy_). Skryp _kontroler_ zawiera zarówno lokalizację robota na mapie oraz samo działanie odbioru i dostarczania paczek. Skrypt _paczki2_  zawiera implementacje uzupełniania paczek po ich odebraniu przez robota.\
Film prezętujący poruszanie się po przykładowo zaplanowanej trajektorii: https://youtu.be/Q14Kbg1jnDU



