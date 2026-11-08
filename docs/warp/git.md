Lp.	Komenda	Przykład użycia	Opis
1.	git clone	git clone URL	Pobranie repozytorium i utworzenie lokalnego katalogu.
2.	git status	git status	Sprawdzenie gałęzi oraz plików zmienionych i przygotowanych.
3.	git add	git add docs/warp/git.md	Dodanie konkretnego pliku do obszaru staging.
4.	git commit	git commit -m "docs: add Git cheatsheet"	Zapis przygotowanych zmian z czytelnym komunikatem.
5.	git push	git push -u origin feature/git-cheatsheet	Publikacja nowej gałęzi i ustawienie śledzenia.
6.	git pull	git pull --ff-only origin main	Pobranie zmian bez tworzenia nieoczekiwanego merge commita.
7.	git fetch	git fetch origin	Pobranie informacji o zmianach bez modyfikowania plików roboczych.
8.	git branch	git branch	Wyświetlenie lokalnych gałęzi i oznaczenie aktywnej.
9.	git switch	git switch -c feature/nazwa	Utworzenie gałęzi roboczej i przełączenie na nią.
10.	git log	git log --oneline -5	Skrócony podgląd pięciu ostatnich commitów.