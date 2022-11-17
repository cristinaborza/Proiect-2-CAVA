1. Bibliotecile care trebuie incluse pentru rularea proiectului sunt urmatoarele:

opencv-python==4.5.3.56
numpy==1.19.2
tensorflow==2.5.0
matplotlib

2. Pentru rularea proiectului sunt necesare urmatoarele:

script: main.py
functie: find_solution(test_path, output_path_task1, output_path_task2), unde:
	- test_path reprezinta path-ul catre folderul unde se afla imaginile de testare
	- output_path_task1 reprezinta path-ul unde sa se salveze fisierele pentru task-ul 1
	- output_path_task2 reprezinta path-ul unde sa se salveze fisierele pentru task-ul 2

Pentru rularea proiectului este nevoie sa se salveze modelul trimis (model.h5, model.json) si, la liniile 20 si 25, trebuie pus path-ul corect catre aceste fisiere.

Pentru reantrenarea modelului trebuie rulat scriptul model.py, iar la liniile 91 si 92 trebuie specificata calea catre datele de antrenare, respectiv validare.

Obs. Folderele in care se vor pune rezultatele pentru cele 2 task-uri trebuie sa fie deja create.
