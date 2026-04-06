# Faza 7: Optymalizacja

## Cel

Ciągłe doskonalenie działań marketingowych na podstawie danych, testów A/B i wniosków AI.

## Proces ciągły — cykl co 2-4 tygodnie

## Krok 1: Cykl optymalizacji

```
    ┌─────────────┐
    │  1. MIERZ   │ ← Zbieraj dane z Analytics, social media, CRM
    └──────┬──────┘
           ↓
    ┌─────────────┐
    │ 2. ANALIZUJ │ ← Identyfikuj wzorce: co działa, co nie
    └──────┬──────┘
           ↓
    ┌─────────────┐
    │ 3. HIPOTEZA │ ← Sformułuj hipotezę: "jeśli zmienimy X, to Y wzrośnie o Z%"
    └──────┬──────┘
           ↓
    ┌─────────────┐
    │  4. TESTUJ  │ ← A/B test lub eksperyment
    └──────┬──────┘
           ↓
    ┌─────────────┐
    │ 5. WDRAŻAJ  │ ← Wdróż zwycięski wariant, dokumentuj wynik
    └──────┬──────┘
           ↓
    (powrót do kroku 1)
```

## Krok 2: Testy A/B

### Co testować (priorytet od najwyższego)

| Element | Wpływ na wynik | Łatwość testu | Przykład |
|---------|---------------|---------------|---------|
| Nagłówek e-maila | Bardzo wysoki | Łatwy | "Jak zaoszczędzić 10h" vs "3 sposoby na automatyzację" |
| CTA (call-to-action) | Wysoki | Łatwy | "Umów konsultację" vs "Sprawdź cennik" |
| Landing page | Wysoki | Średni | Z wideo vs bez wideo |
| Format treści | Średni | Łatwy | Karuzela vs pojedynczy obraz |
| Godzina publikacji | Średni | Łatwy | 9:00 vs 12:00 vs 18:00 |
| Grupa docelowa reklam | Wysoki | Średni | Wiek 25-35 vs 35-45 |
| Kreacja reklamowa | Bardzo wysoki | Średni | Statyk vs wideo vs karuzela |

### Zasady testowania

1. **Testuj jedną zmienną** — nigdy dwie naraz
2. **Minimum 100 obserwacji** na wariant (np. 100 otwarć e-maila)
3. **Minimum 7 dni** trwania testu
4. **Dokumentuj każdy test** — hipoteza, warianty, wynik, wniosek
5. **Implementuj zwycięzcę** — nie zostawiaj wyników w szufladzie

### Karta testu A/B

```
Test #: [numer]
Data: [start — koniec]
Element: [co testujemy]
Hipoteza: "Jeśli [zmiana], to [metryka] wzrośnie/spadnie o [%]"

Wariant A (kontrola): [opis]
Wariant B (test): [opis]

Metryka główna: [np. CTR, open rate, konwersja]
Metryka pomocnicza: [np. bounce rate, czas na stronie]

Wynik:
- Wariant A: [wartość metryki]
- Wariant B: [wartość metryki]
- Różnica: [%]
- Istotność statystyczna: [tak/nie]

Wniosek: [co to oznacza]
Akcja: [co wdrażamy]
```

## Krok 3: AI-driven insights

### Analiza danych z AI

Co miesiąc eksportuj dane i poproś AI o analizę:

```
Oto dane marketingowe mojej firmy z ostatniego miesiąca:

Ruch na stronie:
- Sesje: [X], zmiana m/m: [%]
- Bounce rate: [X]%
- Top 5 stron: [lista]
- Źródła ruchu: [organic X%, social X%, paid X%, direct X%]

Social media:
- LinkedIn: [X] postów, avg engagement [X]%, top post: [opis]
- Instagram: [X] postów, avg reach [X], top post: [opis]
- Facebook: [X] postów, avg reach [X], top post: [opis]

E-mail:
- Wysyłki: [X], avg open rate: [X]%, avg CTR: [X]%
- Najlepszy temat: [tytuł]
- Najgorszy temat: [tytuł]

Konwersje:
- Leady: [X], zmiana m/m: [%]
- Koszt na leada: [X] zł
- Konwersja lead → klient: [X]%

Przeanalizuj:
1. Co działa najlepiej (top 3 z danymi)?
2. Co działa najgorzej (bottom 3 z danymi)?
3. Jakie wzorce widzisz w zachowaniu odbiorców?
4. 5 konkretnych rekomendacji na następny miesiąc z estymacją wpływu
```

## Krok 4: Skalowanie tego co działa

### Framework skalowania

```
             EFEKT
    Wysoki │  SKALUJ    │  TESTUJ
           │  (więcej   │  (więcej wariantów,
           │   budżetu, │   nowe grupy)
           │   częściej)│
    ───────┼────────────┼────────────
    Niski  │  OPTYMALIZUJ│  PORZUĆ
           │  (popraw    │  (przenieś budżet
           │   element)  │   gdzie indziej)
           │             │
           └─────────────┴────────────
              Niski         Wysoki
                    KOSZT
```

### Reguły skalowania

1. **Zwiększaj budżet o max 30%** na raz — nagły skok może zepsuć algorytmy
2. **Skaluj najpierw organiczne** — content, SEO, newsletter (trwały efekt)
3. **Reklamy skaluj dopiero po 3 tygodniach** stabilnych wyników
4. **Dokumentuj punkt nasycenia** — kiedy więcej budżetu nie daje proporcjonalnie więcej wyników

## Krok 5: Raportowanie

### Raport miesięczny

Użyj szablonu [`/templates/raport-miesięczny.md`](../templates/raport-miesięczny.md).

### Cadence spotkań

| Spotkanie | Częstotliwość | Czas | Uczestnicy |
|-----------|-------------|------|------------|
| Quick check metryki | Poniedziałek | 15 min | Marketing team |
| Review tygodniowy | Piątek | 30 min | Marketing + właściciel |
| Raport miesięczny | 1. dzień miesiąca | 60 min | Wszyscy stakeholders |
| Review kwartalny | Co 3 mies. | 2h | Strategia — cele, budżet, kierunek |

## Krok 6: Pętla uczenia się

Po każdym cyklu optymalizacji (co miesiąc):

1. **Co zadziałało?** — zapisz w "bank wiedzy" firmy
2. **Co nie zadziałało?** — zapisz dlaczego (nie powtarzaj błędów)
3. **Co nas zaskoczyło?** — nowy insight o klientach
4. **Co zmieniamy na następny miesiąc?** — max 3 zmiany

---

## Następne kroki

Po pierwszym pełnym cyklu (7 faz):
- Wróć do Fazy 1 i przeprowadź mini-audyt (skrócony, 1-2 dni)
- Zaktualizuj cele na następny kwartał (Faza 2)
- Iteruj strategię na podstawie danych (Faza 3)
- Cykl się powtarza, ale za każdym razem szybciej i z lepszymi danymi
