# Průvodce přežitím: Jak ovládnout Python

Vítejte v mém prvním profesionálním projektu na GitHubu! Tento dokument slouží jako **stručný návod a přehled** pro každého, kdo se chce rychle zorientovat v programu Python a využít jeho sílu na maximum.

---

## 1. Architektura dokumentu

Python je jedním z nejpopulárnějších programovacích jazyků na světě. Níže se podíváme na jeho hlavní pilíře, syntaxi a užitečné triky pro každodenní kódování.

### 1.1 Proč zrovna Python?
Python kombinuje **velkou sílu** s velmi čistou a srozumitelnou syntaxí. Je ideální pro začátečníky i pokročilé vývojáře.

### 1.2 Základní filozofie jazyka
Kód se čte častěji, než se píše. Proto je důležité dbát na přehlednost, dodržovat konvence a psát čistý kód.

---

## 2. Emoce a důraz v textu

Při programování občas narazíme na situace, kdy si říkáme: *„Proč tohle nefunguje?!“*. 
* **Klíčové pravidlo:** **Vždy čtěte chybové hlášky (traceback) odspodu nahoru.**
* ~~Starý způsob ladění přes `print()` příkazy~~ už dávno nahradily moderní debuggery.

---

## 3. Organizace myšlenek

Zde je můj osobní checklist pro úspěšné dokončení každého programátorského projektu:

* [x] Návrh architektury a struktury složek
* [x] Napsání základní logiky programu a testů[cite: 1]
* [ ] Vytvoření přehledné dokumentace (tento soubor `README.md`)[cite: 1]
* [ ] Závěrečný kódový audit (code review) a nasazení[cite: 1]

1. Analýza problému a rozvržení funkcí.
2. Samotná implementace kódu.
3. Testování a ladění chyb.

---

## 4. Propojení světa: Odkazy a Obrázky

### 4.1 Odkazy
Prohlubte své znalosti a navštivte oficiální [Dokumentaci jazyka Python](https://www.python.org/) nebo se podívejte na tutoriály na [Real Python](https://realpython.com/)[cite: 1].

### 4.2 Obrázky
Níže můžete vidět ilustrační ukázku loga nebo prostředí:
![Logo Pythonu a vývojové prostředí](images/obrazek.png)[cite: 1]

---

## 5. Digitální laboratoř (Ukázka kódu)

Následující ukázka v Pythonu demonstruje jednoduchou funkci pro výpočet faktoriálu:

```python
def vypocet_faktorialu(n):
    """Vrátí faktoriál zadaného čísla n."""
    if n < 0:
        return "Faktoriál záporného čísla neexistuje."
    vysledek = 1
    for i in range(1, n + 1):
        vysledek *= i
    return vysledek

# Příklad použití:
print(vypocet_faktorialu(5))  # Výsledek: 120
