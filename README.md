# 🎸 Riff Studio

### Wielościeżkowy program do komponowania gitar, basu, perkusji i pianina

**Windows • Tauri 2 • React • TypeScript • alphaTab • Web Audio API**

**Riff Studio 1.0 — przygotowanie wydania**  
Aktualna wersja testowana przed publikacją: **1.0 RC3.3**

[**📥 Instalatory i wydania**](https://github.com/vodnik-33/riff-studio-releases/releases) · [**🐛 Zgłaszanie błędów**](https://github.com/vodnik-33/riff-studio-releases/issues)

</div>

---

## Czym jest Riff Studio?

**Riff Studio** to aplikacja desktopowa dla Windows przeznaczona do tworzenia riffów, szkicowania aranżacji i komponowania utworów wielościeżkowych. Łączy edytor tabulatury gitarowej, sekwencer perkusyjny, piano roll oraz mikser w jednym środowisku.

Projekt rozwijany jest z myślą o muzyce gitarowej — od cleanów i heavy metalu po bardziej rozbudowane aranżacje symphonic black metalu. Nie wymaga od użytkownika instalowania Node.js ani narzędzi programistycznych.

## ✨ Najważniejsze możliwości

| Obszar | Funkcje |
| --- | --- |
| 🎸 **Gitara** | Tabulatura, edycja progów bezpośrednio w podglądzie alphaTab, strojenia i techniki gitarowe |
| 🎸 **Bas** | Ścieżki basowe 4- i 5-strunowe, strojenie strun |
| 🥁 **Perkusja** | Sekwencer rytmiczny, presety i przejścia, w tym cztery tomy |
| 🎹 **Pianino** | Piano roll, odsłuch nut podczas edycji, brzmienie samplowanego fortepianu |
| 🎚️ **Mikser** | Głośność, panorama stereo, Mute i Solo dla ścieżek |
| ▶️ **Transport** | Play od wybranego taktu, Pause z zachowaniem pozycji, Stop z powrotem na początek, metronom |
| 🔁 **Loop** | Zaznaczanie i zapętlanie zakresu pełnych taktów na osi czasu i w podglądzie partytury |
| 💾 **Projekty** | Zapis lokalny, eksport i import projektów JSON |
| 🎼 **MIDI** | Import i eksport MIDI dla pianina i perkusji |
| 🔊 **Audio** | Eksport miksu do WAV oraz osobnych ścieżek |
| 🎨 **Interfejs** | Wielościeżkowy układ DAW i sześć motywów kolorystycznych |

Riff Studio obsługuje **do 16 ścieżek** w projekcie.

## 📥 Pobieranie i instalacja — Windows

1. Otwórz stronę [**Riff Studio — Releases**](https://github.com/vodnik-33/riff-studio-releases/releases).
2. Wybierz najnowsze opublikowane wydanie i pobierz instalator Windows **`.exe`** z sekcji **Assets**.
3. Uruchom instalator i postępuj zgodnie z instrukcjami na ekranie.
4. Uruchom **Riff Studio** z menu Start lub ze skrótu na pulpicie.

> **Uwaga:** instalator może być niepodpisany cyfrowo, dlatego Windows może wyświetlić ostrzeżenie o nieznanym wydawcy. Pobieraj aplikację wyłącznie z oficjalnej strony wydań i nie wyłączaj zabezpieczeń systemu.

> Wydanie **1.0** zostanie oznaczone jako stabilne dopiero po zakończeniu testów. Do tego momentu korzystaj z dostępnej wersji testowej i twórz kopie projektów.

## 🚀 Szybki start

1. **Utwórz projekt** i ustaw tempo.
2. **Dodaj ścieżki** gitar, basu, perkusji lub pianina.
3. **Wpisuj nuty** w tabulaturze alphaTab albo w piano roll; rytmy perkusji ustawiaj w sekwencerze.
4. **Odtwarzaj od wybranego miejsca** na osi czasu lub użyj narzędzia **Ustaw start**.
5. Użyj **Pause**, aby wstrzymać i wznowić odtwarzanie, lub **Stop**, aby wrócić do początku utworu.
6. Zaznacz wybrane takty narzędziem **Zaznacz Loop**, jeśli chcesz ćwiczyć lub odsłuchiwać fragment w pętli.
7. **Zapisz kopię projektu w JSON**; w razie potrzeby wyeksportuj także MIDI lub WAV.

### Obsługa tabulatury

W podglądzie alphaTab dostępne są trzy narzędzia: **Edycja**, **Ustaw start** oraz **Zaznacz Loop**. W trybie edycji kliknij konkretną cyfrę progu i zmień jej wartość klawiaturą. Strzałki przemieszczają zaznaczenie, a Delete usuwa nutę z wybranej pozycji.

W standardowej tabulaturze gitarowej **struna najcieńsza jest na górze**, a **najgrubsza na dole**.

### Projekty i kompatybilność

- **JSON** — format wymiany i tworzenia kopii projektów Riff Studio; przed aktualizacją programu warto wyeksportować projekt na dysk.
- **MIDI** — obecnie import i eksport obejmuje **pianino i perkusję**. Import działa w ramach obsługiwanej siatki rytmicznej; nie jest to pełna wymiana wszystkich danych aranżacji z dowolnym DAW.
- **WAV** — format do odsłuchu i dalszej obróbki nagrań poza Riff Studio.

## 🧪 Status wydania 1.0

Zamknęliśmy główne prace funkcjonalne i testujemy kandydatów do wydania 1.0. W ostatnich iteracjach dopracowano m.in.:

- numerację strun i edycję istniejących nut w alphaTab,
- wybór taktu rozpoczęcia odtwarzania,
- rozdzielenie **Play / Pause / Stop**,
- wybór, podświetlanie i odtwarzanie zakresu **Loop**,
- eksport projektów JSON w wersji desktopowej,
- import i eksport MIDI pianina i perkusji,
- nową ikonę aplikacji Windows **RS**.

Przed oznaczeniem wydania jako stabilne weryfikujemy instalator, zachowanie istniejących projektów, eksporty oraz działanie wszystkich instrumentów na Windows.

## 🐛 Testy i zgłaszanie błędów

Jeśli testujesz program, przekaż przy zgłoszeniu:

1. **Wersję aplikacji** i wersję Windows.
2. **Opis problemu** i kroki prowadzące do jego odtworzenia.
3. **Oczekiwany** i **rzeczywisty** rezultat.
4. Zrzut ekranu lub krótkie nagranie, jeśli pomagają zrozumieć problem.
5. Opcjonalnie przykładowy plik projektu **bez danych prywatnych**.

Zgłoszenia można zamieszczać w zakładce [**Issues repozytorium wydań**](https://github.com/vodnik-33/riff-studio-releases/issues), jeśli jest włączona.

## 🛠️ Uruchomienie z kodu źródłowego

Ta sekcja jest przeznaczona dla osób mających dostęp do prywatnego repozytorium deweloperskiego.

**Wymagania:** Node.js, npm; do budowania aplikacji Windows również Rust i wymagane narzędzia Tauri 2.

```powershell
npm.cmd install
npm.cmd run build
npm.cmd run dev
```

Wersja desktopowa w trybie deweloperskim:

```powershell
npm.cmd run desktop:dev
```

Budowanie instalatora Windows:

```powershell
npm.cmd run desktop:build
```

Automatyczne kompilacje instalatora Windows są przygotowane w **GitHub Actions**. Publikacja gotowych instalatorów odbywa się w osobnym repozytorium `riff-studio-releases`.

## 📌 Plany po 1.0

W kolejnych wersjach rozważamy m.in. podgląd partytury perkusyjnej, dalsze usprawnienia pracy z MIDI oraz rozwój edytorów i brzmień. Zakres aktualizacji będzie zależał od wyników testów i opinii użytkowników.

## ℹ️ Informacje

**Projekt:** Riff Studio  
**Platforma:** Windows  
**Autor / GitHub:** [vodnik-33](https://github.com/vodnik-33)  
**Dystrybucja:** [riff-studio-releases](https://github.com/vodnik-33/riff-studio-releases)

Wykorzystane komponenty i materiały audio podlegają odpowiednim licencjom ich autorów. Przed dalszą redystrybucją sampli należy sprawdzić warunki poszczególnych zestawów.

---

<div align="center">

**Riff Studio — Compose. Arrange. Create.**

</div>
