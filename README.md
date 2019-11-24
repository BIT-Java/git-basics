Wprowadzenie do Gita
-----------------------

### Polecenia:

* `git init` - zaincjalizowanie nowego repozytorium Git w aktualnym folderze
* `git clone <url>` - pobranie repozytorium (np. z githuba)
* `git add <file>` - dodanie pliku do repozytorium Git
* `git add --all` - dodanie wszystkich plików w obrębie folderu do repozytorium Git
* `git commit -m <message>` - utworzenie rewizji z danym opisem/wiadomością
* `git remote add <remote_name> <url>` - połączenie ze zdalnym repozytorium (np. na githubie) -> np. `git remote add origin https://github.com/BIT-Java/git-basics.git`
* `git remote remove <remote_name>` - usunięcie połączenia ze zdalnym repozytorium
* `git push <remote_name> <branch_name>` - wysłanie zmian na zdalne repozytorium
* `git pull <remote_name> <branch_name>` - pobranie zmian ze zdalnego repozytorium
* `git checkout <branch_name>` - przełączenie na gałąź o danej nazwie
* `git branch <branch_name>` - utworzenie gałęzi o danej nazwie
* `git checkout -b <branch_name>` - utworzenie gałęzi o danej nazwie i przełączenie na nią
* `git branch -d <branch_name>` - usunięcie gałęzi o danej nazwie
* `git merge <branch_name>` - zmergowanie gałęzi o danej nazwie z aktualną gałęzią
* `git rebase <branch_name>` - wykonanie operacji rebase gałęzi o danej nazwie z aktualną gałęzią


### Nazewnictwo gałęzi:

Jedna z konwencji nazywania poszczególnych gałęzi fajnie przedstawiona w tym artykule:

https://gist.github.com/digitaljhelms/4287848


### Operacja merge:

Dokładny opis (wraz z przykładami) jak działa polecenie merge: 

https://git-scm.com/docs/git-merge


### Operacja rebase:

Dokładny opis (wraz z przykładami) jak działa polecenie rebase: 

https://git-scm.com/docs/git-rebase


### Przydatne linki:

* https://git-scm.com/docs/git - dokumentacja Gita
* https://learngitbranching.js.org/ - wizualizacja jak działają poszczególne polecenia (w tym tworzenie gałęzi, operacje merge i rebase)
