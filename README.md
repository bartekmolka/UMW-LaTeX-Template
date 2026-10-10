# Szablon LaTeX dla Uniwersytetu Medycznego we Wrocławiu (UMW)

Nieoficjalny szablon prezentacji Beamer oraz dokumentów w systemie LaTeX, dostosowany do identyfikacji wizualnej **Uniwersytetu Medycznego im. Piastów Śląskich we Wrocławiu**.

> ⚠️ **Uwaga (Disclaimer):** Project jest inicjatywą prywatną/społecznościową i **nie jest** oficjalnie wspierany ani zatwierdzony przez Uniwersytet Medyczny we Wrocławiu.

---

## 🎨 Identyfikacja Wizualna

Szablon wykorzystuje oficjalną paletę barw UMW:
* **Granatowy / Ciemny:** `#2B2B5C`
* **Złoty UMW:** `#D0A53E`
* **Szary (tło bloków):** `#F4F4F4`

---

## 🚀 Jak zacząć?

### 1. Pobieranie logo
Ze względów prawnych repozytorium **nie zawiera** oficjalnych plików graficznych / logotypów uczelni.
1. Pobierz oficjalne logo w formacie `.png` lub `.pdf` ze strony uczelni lub intranetu UMW.
2. Umieść plik w głównym katalogu projektu i zmień jego nazwę na `logo_umw.png` (lub zaktualizuj ścieżkę w kodzie pliku `.tex`).

### 2. Kompilacja
Szablon można kompilować za pomocą standardowych silników LaTeX:
* `pdfLaTeX`
* `XeLaTeX` / `LuaLaTeX` (zalecane w przypadku używania niestandardowych czcionek systemowych)

Możesz również po prostu wgrać pliki projektu do serwisu **Overleaf**.

---

## 📁 Struktura Projektu

* `main.tex` – główny plik prezentacji / dokumentu
* `beamercolorthemeUMW.sty` – definicja kolorystyki UMW dla prezentacji Beamer
* `README.md` – instrukcja i informacje o projekcie

---

## 🙏 Podziękowania i Źródła

Projekt powstał na bazie repozytorium [polaksta/LaTeX](https://github.com/polaksta/LaTeX), z którego zaczerpnięto podstawową strukturę, a następnie dostosowano ją do wytycznych wizualnych UMW.

---

## 📄 Licencja

Kod źródłowy szablonu udostępniony jest na licencji [MIT](LICENSE). Możesz go swobodnie modyfikować i używać do własnych celów akademickich i prywatnych.
