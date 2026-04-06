# Faza 5: Automatyzacja

## Cel

Wdrożenie narzędzi i workflow, które automatyzują powtarzalne zadania marketingowe.

## Czas realizacji: 7-10 dni

## Krok 1: Audyt zadań do automatyzacji

Przejrzyj codzienne/tygodniowe zadania marketingowe i oceń potencjał automatyzacji:

| Zadanie | Czas/tyg. | Powtarzalność | Automatyzacja | Narzędzie |
|---------|----------|---------------|---------------|-----------|
| Publikacja postów social media | 3h | Wysoka | Pełna | Buffer/Postiz |
| Odpowiedzi na komentarze | 2h | Średnia | Częściowa | Szablon + AI draft |
| Tworzenie grafik | 4h | Wysoka | Częściowa | Canva + szablony |
| Wysyłka newslettera | 2h | Wysoka | Pełna | Mailerlite automation |
| Raportowanie | 3h | Wysoka | Pełna | Google Data Studio |
| Follow-up z leadami | 2h | Wysoka | Częściowa | CRM + automation |
| Monitoring wzmianek | 1h | Wysoka | Pełna | Google Alerts + Brand24 |

### Reguła automatyzacji

**Automatyzuj, jeśli zadanie spełnia 2 z 3 kryteriów:**
1. Powtarza się >2x w tygodniu
2. Zajmuje >30 minut za każdym razem
3. Ma jasne reguły (if → then)

## Krok 2: Stos narzędzi

### Wariant budżetowy (0-200 zł/mies.)

| Funkcja | Narzędzie | Koszt |
|---------|-----------|-------|
| Scheduler social media | Buffer (darmowy) | 0 zł |
| E-mail marketing | Mailerlite (darmowy do 1000) | 0 zł |
| Grafiki | Canva (darmowy) | 0 zł |
| AI copywriting | ChatGPT Free | 0 zł |
| Analityka | Google Analytics | 0 zł |
| CRM | HubSpot (darmowy) | 0 zł |
| **Suma** | | **0 zł** |

### Wariant standardowy (200-500 zł/mies.)

| Funkcja | Narzędzie | Koszt |
|---------|-----------|-------|
| Scheduler + analityka | Buffer Pro | 60 zł |
| E-mail + automatyzacje | Mailerlite (Growing) | 60 zł |
| Grafiki + brand kit | Canva Pro | 50 zł |
| AI copywriting | ChatGPT Plus | 90 zł |
| SEO | Ubersuggest | 50 zł |
| Monitoring | Google Alerts + Brand24 starter | 150 zł |
| **Suma** | | **~460 zł** |

### Wariant premium (500-1500 zł/mies.)

| Funkcja | Narzędzie | Koszt |
|---------|-----------|-------|
| Social media suite | Hootsuite Pro | 200 zł |
| E-mail + CRM | ActiveCampaign | 200 zł |
| AI copywriting + vision | ChatGPT Plus + Claude Pro | 180 zł |
| Grafiki + wideo | Canva Pro + InVideo | 100 zł |
| SEO + content | Semrush/Ahrefs | 400 zł |
| Automatyzacja workflow | Make.com/N8N | 100 zł |
| **Suma** | | **~1180 zł** |

## Krok 3: Kluczowe workflow

### Workflow 1: Automatyczna publikacja treści

```
Trigger: Nowy artykuł na blogu
    ↓
Akcja 1: Wygeneruj 3 posty social media (AI)
    ↓
Akcja 2: Zaplanuj publikację (Buffer)
    - LinkedIn: wtorek 9:00
    - Facebook: środa 12:00
    - Instagram: czwartek 18:00
    ↓
Akcja 3: Dodaj link do newslettera (Mailerlite)
    ↓
Akcja 4: Zaktualizuj raport (Google Sheets)
```

### Workflow 2: Nurturing leadów

```
Trigger: Nowy kontakt w CRM / formularz na stronie
    ↓
Dzień 0: E-mail powitalny z wartościowym PDF-em
    ↓
Dzień 3: E-mail z case study (najlepszy dla branży leada)
    ↓
Dzień 7: E-mail z zaproszeniem na konsultację
    ↓
Dzień 14: E-mail z ofertą specjalną (jeśli nie konwertował)
    ↓
Po konwersji: Przenieś do segmentu "klient" → inna sekwencja
Bez konwersji po 30 dniach: Przenieś do "cold" → newsletter ogólny
```

### Workflow 3: Raportowanie automatyczne

```
Trigger: 1. dzień miesiąca, 8:00
    ↓
Akcja 1: Pobierz dane z Google Analytics (API)
    ↓
Akcja 2: Pobierz dane z social media (API)
    ↓
Akcja 3: Pobierz dane z Mailerlite (API)
    ↓
Akcja 4: Wypełnij szablon raportu (Google Sheets)
    ↓
Akcja 5: Wyślij raport na e-mail (zespół + klient)
```

## Krok 4: Konfiguracja triggerów

### Typy triggerów

| Typ | Przykład | Narzędzie |
|-----|---------|-----------|
| Czasowy | "Co poniedziałek o 9:00" | Cron / Make.com |
| Zdarzeniowy | "Nowy lead w formularzu" | Webhook |
| Warunkowy | "Jeśli open rate <15%" | Mailerlite rules |
| Manualny | "Kliknij przycisk" | Dashboard / CRM |

### Testowanie automatyzacji

Przed uruchomieniem na żywo:
1. **Test z danymi testowymi** — użyj fikcyjnych adresów e-mail
2. **Test edge cases** — co się stanie jeśli lead nie ma e-maila? Jeśli API nie odpowiada?
3. **Monitoruj pierwsze 7 dni** — sprawdzaj logi codziennie
4. **Ustaw alerty** — powiadomienie gdy automatyzacja się wywali

## Krok 5: Dokumentacja workflow

Dla każdego workflow stwórz kartę:

```
Nazwa: [nazwa workflow]
Cel: [co automatyzuje i dlaczego]
Trigger: [co go uruchamia]
Kroki: [lista akcji]
Narzędzia: [jakie integracje]
Właściciel: [kto odpowiada za monitoring]
Fallback: [co zrobić jeśli się zepsuje]
Ostatnia aktualizacja: [data]
```

## Prompt AI do automatyzacji

```
Zaprojektuj plan automatyzacji marketingu dla firmy [nazwa]:

Obecne zadania marketingowe (tygodniowo):
[lista zadań z czasem]

Narzędzia już używane: [lista]
Budżet na narzędzia: [X] zł/mies.
Umiejętności techniczne zespołu: [podstawowe/średnie/zaawansowane]

Zaproponuj:
1. Top 5 zadań do automatyzacji (z estymacją oszczędności czasu)
2. Stos narzędzi (z kosztami)
3. 3 kluczowe workflow z diagramami
4. Plan wdrożenia (kolejność, tygodnie)
```

→ **Następna faza**: [`06-wdrozenie.md`](06-wdrozenie.md)
