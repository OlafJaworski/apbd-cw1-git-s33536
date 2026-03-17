.
 ** Dlaczego merge nie był fast-forward?
  - Dlatego że po utworzeniu feature-max w mainie stworzony został inny niezależny commit i chronologia się rozeszła i trzeba było połączyć dwie oddzielne gałęzie w jedną.

** Czym w praktyce różni się merge od rebase? 
  - merge zostawia prawdziwą historię commitów, ale może się zrobić chaotyczny, dużo galęzi i ich sklejania, a rebase odcina obecną gałąź i dokleja ją na końcu maina, co robi jedną długą linie

*** W jaki sposób został rozwiązany konflikt w repozytorium?
  - podczas łączenia dwóch zmian w jednej linijce rozwiązałem go manualnie poprzez resolve conflicts i zapisaniem samemu co tam powinno być i potwierdziłem commitem

