# Faza 6: Wdrożenie

## Cel

Przełożenie strategii i planów na konkretne działania w zarządzalnych sprintach.

## Czas realizacji: 4-8 tygodni (w zależności od skali)

## Krok 1: Planowanie sprintów

### Sprint 0 — Przygotowanie (tydzień 1)

- [ ] Założenie/konfiguracja wszystkich kont w narzędziach
- [ ] Podłączenie integracji (API, webhooks)
- [ ] Stworzenie szablonów graficznych (Canva brand kit)
- [ ] Przygotowanie pierwszych 10 treści (bank na 2 tygodnie)
- [ ] Konfiguracja Google Analytics / Tag Manager
- [ ] Konfiguracja UTM-ów dla śledzenia kampanii
- [ ] Test wszystkich automatyzacji z danymi testowymi

### Sprint 1 — Soft Launch (tydzień 2-3)

- [ ] Uruchomienie publikacji w 1-2 kanałach (najsilniejszych)
- [ ] Pierwsza wysyłka newslettera
- [ ] Aktywacja workflow nurturing
- [ ] Monitoring: codziennie sprawdzaj metryki i logi
- [ ] Zbieraj feedback od zespołu

### Sprint 2 — Rozszerzenie (tydzień 4-5)

- [ ] Dodanie kolejnych kanałów
- [ ] Uruchomienie płatnych reklam (jeśli w budżecie)
- [ ] Pierwszy A/B test (nagłówek, CTA lub grafika)
- [ ] Optymalizacja na podstawie danych z Sprint 1

### Sprint 3 — Pełna operacja (tydzień 6-8)

- [ ] Wszystkie kanały aktywne
- [ ] Wszystkie automatyzacje działają
- [ ] Pierwszy raport miesięczny
- [ ] Ewaluacja: co działa, co wymaga korekty

## Krok 2: Macierz odpowiedzialności (RACI)

| Zadanie | Właściciel firmy | Marketing manager | Freelancer/Agencja |
|---------|-----------------|-------------------|-------------------|
| Strategia i decyzje | **A** (Accountable) | **R** (Responsible) | **C** (Consulted) |
| Tworzenie treści | I | R / A | R |
| Publikacja | I | A | R |
| Reklamy płatne | A | C | R |
| Raportowanie | I | A | R |
| Budżet | A | R | I |
| Kontakt z klientami | R | C | I |

**R** = Responsible (wykonuje), **A** = Accountable (odpowiada), **C** = Consulted (konsultowany), **I** = Informed (informowany)

## Krok 3: Rollout kanał po kanale

### Kolejność uruchamiania (rekomendowana)

```
Tydzień 1-2:  [Kanał #1 — najsilniejszy] ─────────────────────→
Tydzień 2-3:  [Kanał #2 — drugi priorytet] ───────────────────→
Tydzień 3-4:  [E-mail marketing] ──────────────────────────────→
Tydzień 4-5:  [Reklamy płatne — jeśli planowane] ──────────────→
Tydzień 5-6:  [Pozostałe kanały] ──────────────────────────────→
Tydzień 6-8:  [Optymalizacja wszystkich kanałów jednocześnie] ─→
```

### Kryteria uruchomienia kanału

Przed uruchomieniem każdego kanału sprawdź:

- [ ] Profil/konto jest kompletne (bio, zdjęcie, link do strony)
- [ ] Minimum 5 postów zaplanowanych na przód
- [ ] Szablony graficzne gotowe
- [ ] Osoba odpowiedzialna wyznaczona
- [ ] KPI dla kanału zdefiniowane
- [ ] Narzędzie do schedulowania skonfigurowane

## Krok 4: Zarządzanie ryzykiem

| Ryzyko | Prawdopodobieństwo | Wpływ | Mitygacja |
|--------|-------------------|-------|-----------|
| Brak czasu na tworzenie treści | Wysokie | Wysoki | Batch content, AI drafts, outsourcing |
| Niski engagement na start | Wysokie | Średni | Normalne — budowanie zasięgu trwa 3-6 mies. |
| Przekroczenie budżetu reklam | Średnie | Wysoki | Dzienny limit budżetu, alerty |
| Negatywne komentarze | Niskie | Średni | Procedura odpowiedzi, szablony |
| Awaria narzędzia | Niskie | Średni | Backup plan, alternatywne narzędzie |

### Plan B dla typowych problemów

**"Nie mam czasu na treści"**
→ Zmniejsz częstotliwość o 50%, ale utrzymaj jakość. Lepiej 2 dobre posty niż 5 przeciętnych.

**"Nikt nie reaguje na posty"**
→ Normalne przez pierwsze 1-3 miesiące. Nie rezygnuj. Analizuj, co ma najlepszy engagement i rób więcej tego.

**"Reklamy nie konwertują"**
→ Sprawdź landing page (szybkość, CTA, wartość). Przetestuj inną grupę docelową. Minimum 500 zł wydanych zanim ocenisz.

**"AI generuje słabe treści"**
→ Problem jest w prompcie, nie w AI. Popraw brief, dodaj przykłady, iteruj.

## Krok 5: Checklist wdrożenia

Użyj [`/checklists/checklist-startu.md`](../checklists/checklist-startu.md) przed uruchomieniem.

## Prompt AI do planowania wdrożenia

```
Stwórz plan wdrożenia strategii marketingowej na 8 tygodni:

Kanały do uruchomienia: [lista z priorytetami]
Zespół: [kto, ile godzin]
Budżet: [X] zł/mies.
Narzędzia: [lista skonfigurowanych narzędzi]
Treści gotowe: [ile, jakie formaty]

Zaproponuj:
1. Plan sprintów (tydzień po tygodniu)
2. Macierz RACI
3. Kolejność rollout kanałów
4. Top 5 ryzyk z mitygacją
5. Metryki sukcesu per sprint
```

→ **Następna faza**: [`07-optymalizacja.md`](07-optymalizacja.md)
