### Labolatorium 2

1\. Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)
```bash
head -2 program.c
```
2\. Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head, tail)
```bash
tail -4 program.c
```
3\. W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)
```bash
grep main program.c
```

4\. Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)
```bash
chmod 640 program.c
```

5\. Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.
```bash
cd temp
mv dom/wazne-sprawy praca
```

6\. Zarchiwizuj cały katalog temp. (zip i tar)
```bash
tar -cf temp.tar temp
```

7\. Usuń katalog temp.
```bash
rm -r temp
```

8\. Odtwórz z archiwum katalog temp. (unzip i tar)
```bash
tar -xf temp.tar
```

9\. Posprzątaj na swoim koncie.
```bash
rm temp.tar
mv temp/praca/wazne-sprawy/ temp/dom/
```

