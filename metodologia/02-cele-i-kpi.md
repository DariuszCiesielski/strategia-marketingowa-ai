# Faza 2: Cele i KPI

## Cel

Przekształcenie wyników audytu w mierzalne cele biznesowe i marketingowe z konkretnymi wskaźnikami sukcesu.

## Czas realizacji: 3-5 dni

## Krok 1: Cele biznesowe → cele marketingowe

Każdy cel marketingowy musi wynikać z celu biznesowego:

| Cel biznesowy | Cel marketingowy | Metryka |
|--------------|-----------------|---------|
| Zwiększenie przychodów o 20% | Generowanie 50 leadów/mies. | MQL count |
| Wejście na nowy rynek | 1000 odwiedzin z nowego segmentu | Traffic by segment |
| Budowanie marki eksperta | 500 obserwujących LinkedIn/kwartał | Follower growth |
| Redukcja kosztów pozyskania | Obniżenie CAC o 30% | Cost per acquisition |

## Krok 2: Framework SMART

Każdy cel musi spełniać kryteria SMART:

- **S** (Specific) — konkretny, jednoznaczny
- **M** (Measurable) — mierzalny liczbowo
- **A** (Achievable) — osiągalny przy obecnych zasobach
- **R** (Relevant) — istotny dla biznesu
- **T** (Time-bound) — z określonym terminem

### Przykłady dobrych celów SMART

**Źle**: "Chcemy więcej klientów z internetu"

**Dobrze**: "Do 30.06 zwiększymy liczbę zapytań ofertowych z formularza www z 10 do 25 miesięcznie, wykorzystując content marketing i Google Ads z budżetem 2000 zł/mies."

**Źle**: "Chcemy być bardziej widoczni w social media"

**Dobrze**: "Do 30.09 osiągniemy 2000 obserwujących na firmowym profilu LinkedIn, publikując 3 posty tygodniowo (2 eksperckie + 1 case study), z engagement rate >3%."

## Krok 3: OKR-y (Objectives & Key Results)

Dla większych firm (10+ osób) warto użyć frameworku OKR:

### Przykład OKR na kwartał

**Objective**: Stać się rozpoznawalnym ekspertem w branży [X] w regionie

**Key Results**:
1. KR1: Opublikować 12 artykułów eksperckich na blogu (z SEO)
2. KR2: Zdobyć 3 wzmianki w mediach branżowych
3. KR3: Osiągnąć 500 unikalnych wizyt na blogu miesięcznie
4. KR4: Wygenerować 20 leadów z treści eksperckich

## Krok 4: Dashboard KPI

Skonfiguruj dashboard do śledzenia postępów. Minimum:

### KPI podstawowe (każda firma)

| KPI | Narzędzie | Częstotliwość |
|-----|-----------|--------------|
| Ruch na stronie | Google Analytics | Tygodniowo |
| Źródła ruchu | Google Analytics | Miesięcznie |
| Konwersje (formularze, zakupy) | Google Analytics + CRM | Tygodniowo |
| Koszt pozyskania klienta (CAC) | Excel/Sheets | Miesięcznie |
| Wartość klienta (LTV) | CRM | Kwartalnie |

### KPI social media

| KPI | Narzędzie | Częstotliwość |
|-----|-----------|--------------|
| Zasięg postów | Natywna analityka | Tygodniowo |
| Engagement rate | Natywna analityka | Tygodniowo |
| Wzrost obserwujących | Natywna analityka | Miesięcznie |
| Kliknięcia w linki | UTM + Analytics | Tygodniowo |

### KPI e-mail

| KPI | Narzędzie | Częstotliwość |
|-----|-----------|--------------|
| Rozmiar listy | Mailerlite/ConvertKit | Miesięcznie |
| Open rate | Narzędzie e-mail | Per wysyłka |
| Click rate | Narzędzie e-mail | Per wysyłka |
| Unsubscribe rate | Narzędzie e-mail | Miesięcznie |

## Krok 5: Benchmarki branżowe

Zanim ustalisz cele, sprawdź benchmarki dla swojej branży:

| Metryka | B2B usługi | E-commerce | SaaS | Lokalna firma |
|---------|-----------|------------|------|--------------|
| Conversion rate (www) | 2-5% | 1-3% | 3-7% | 5-10% |
| Email open rate | 20-25% | 15-20% | 25-30% | 20-30% |
| LinkedIn engagement | 2-4% | 1-2% | 3-5% | 2-4% |
| CAC (koszt pozyskania) | 200-1000 zł | 50-200 zł | 100-500 zł | 30-150 zł |

## Prompt AI do definiowania celów

```
Na podstawie audytu marketingowego firmy [nazwa]:

Wyniki audytu:
- Ruch na stronie: [X] wizyt/mies.
- Konwersja: [X]%
- Główne kanały: [lista]
- Budżet: [X] zł/mies.
- Zespół: [X] osób, [X] godzin/tydzień

Zaproponuj:
1. 3 cele SMART na najbliższy kwartał (90 dni)
2. OKR-y z key results dla każdego celu
3. Dashboard KPI — jakie metryki śledzić i jak często
4. Realistyczne benchmarki dla branży [branża]

Uwzględnij ograniczenia budżetowe i kadrowe.
```

→ **Następna faza**: [`03-strategia.md`](03-strategia.md)
