# Faza 1: Audyt marketingowy

## Cel

Zbudowanie pełnego obrazu obecnej sytuacji marketingowej firmy — co działa, co nie, gdzie są szanse, a gdzie zagrożenia.

## Czas realizacji: 5-7 dni

## Krok 1: Audyt obecności online

### Strona internetowa
- [ ] Czy strona jest responsywna (mobile-first)?
- [ ] Jaki jest czas ładowania? (cel: <3s, narzędzie: PageSpeed Insights)
- [ ] Czy jest SSL (https)?
- [ ] Czy meta tagi (title, description) są wypełnione na kluczowych stronach?
- [ ] Czy jest Google Analytics / inny system analityki?
- [ ] Ile unikalnych użytkowników miesięcznie?
- [ ] Jaki jest współczynnik odrzuceń (bounce rate)?
- [ ] Jakie są główne źródła ruchu?

### Social media
Dla każdego kanału (Facebook, Instagram, LinkedIn, TikTok, YouTube):
- [ ] Liczba obserwujących
- [ ] Średni zasięg postu (ostatnie 30 dni)
- [ ] Średni engagement rate
- [ ] Częstotliwość publikacji
- [ ] Typ treści (tekst, grafika, wideo, karuzela)
- [ ] Ton komunikacji

### E-mail marketing
- [ ] Czy jest lista mailingowa? Ile kontaktów?
- [ ] Jakie narzędzie? (Mailerlite, ConvertKit, inne)
- [ ] Średni open rate
- [ ] Średni click rate
- [ ] Częstotliwość wysyłki
- [ ] Czy są automatyzacje (welcome series, abandoned cart)?

## Krok 2: Analiza konkurencji

Wybierz 3-5 bezpośrednich konkurentów i przeanalizuj:

| Aspekt | Konkurent 1 | Konkurent 2 | Konkurent 3 |
|--------|------------|------------|------------|
| Strona www (jakość) | | | |
| Blog (częstotliwość) | | | |
| Social media (kanały) | | | |
| Reklamy (Google/Meta) | | | |
| SEO (pozycje kluczowych fraz) | | | |
| USP (unikalna propozycja wartości) | | | |
| Cennik (jeśli publiczny) | | | |

### Narzędzia AI do analizy konkurencji
- **ChatGPT/Claude**: "Przeanalizuj stronę [URL] pod kątem marketingu. Co robią dobrze, co mogliby poprawić?"
- **SimilarWeb** (darmowy plan): ruch, źródła, benchmark
- **Meta Ad Library**: jakie reklamy puszcza konkurencja

## Krok 3: Analiza SWOT

Na podstawie kroków 1-2 wypełnij macierz:

| | Pozytywne | Negatywne |
|---|-----------|-----------|
| **Wewnętrzne** | **Mocne strony** — co firma robi dobrze w marketingu? Jakie ma zasoby? | **Słabe strony** — czego brakuje? Co nie działa? Gdzie są luki? |
| **Zewnętrzne** | **Szanse** — jakie trendy rynkowe sprzyjają? Jakie nowe kanały można wykorzystać? | **Zagrożenia** — co robi konkurencja? Jakie zmiany algorytmów mogą zaszkodzić? |

## Krok 4: Audyt zasobów

- **Budżet marketingowy**: ile miesięcznie firma może przeznaczyć?
- **Zespół**: kto zajmuje się marketingiem? Ile godzin tygodniowo?
- **Narzędzia**: jakie narzędzia są już opłacane?
- **Treści**: czy jest bank zdjęć, materiałów wideo, artykułów?
- **Dane klientów**: czy jest CRM? Czy dane są uporządkowane?

## Krok 5: Podsumowanie audytu

Wypełnij szablon [`/templates/audyt-template.md`](../templates/audyt-template.md) i przejdź do Fazy 2.

### Czerwone flagi (wymagają natychmiastowej uwagi)
- Strona bez SSL
- Brak Google Analytics
- Bounce rate >70%
- Zero aktywności w social media od >30 dni
- Lista mailingowa <100 kontaktów bez strategii pozyskiwania

## Prompt AI do audytu

```
Jesteś ekspertem od marketingu cyfrowego dla MŚP. Przeprowadź audyt marketingowy 
firmy [nazwa] z branży [branża]. 

Obecna sytuacja:
- Strona: [URL]
- Social media: [lista kanałów z liczbą obserwujących]
- Budżet miesięczny: [kwota]
- Zespół: [liczba osób, godziny]

Przeanalizuj:
1. Mocne strony obecnego marketingu
2. Krytyczne luki do uzupełnienia
3. Quick wins (efekty w <30 dni)
4. Rekomendacje priorytetowe (top 3)

Format: tabela z priorytetem (wysoki/średni/niski), szacowanym kosztem i czasem realizacji.
```

→ **Następna faza**: [`02-cele-i-kpi.md`](02-cele-i-kpi.md)
