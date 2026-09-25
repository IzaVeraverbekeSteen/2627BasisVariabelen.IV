# Praktijkopdrachten: JavaScript Primitieve Variabelen

Met deze 20 eenvoudige opdrachten kun je oefenen met het aanmaken, aanpassen en controleren van primitieve variabelen in JavaScript (`string`, `number`, `boolean`, `null`, `undefined`, en `symbol`).

---

## 1. String (Tekst)

1. **Naam samenvoegen:**
   Maak twee variabelen aan: `voornaam` met jouw voornaam en `achternaam` met jouw achternaam. Voeg ze samen in een variabele `volledigeNaam` en print deze naar de console.

2. **Template literals:**
   Gebruik template literals (backticks `` ` ``) om de volgende zin te maken:  
   `"Hallo, mijn naam is [volledigeNaam] en ik leer JavaScript."`

3. **Tekstlengte:**
   Maak een variabele `woord = "Programmeren"`. Gebruik de `.length` eigenschap om het aantal letters in de console te printen.

4. **Hoofdletters:**
   Maak een variabele `stad = "amsterdam"`. Zet de tekst om naar hoofdletters met `.toUpperCase()` en print het resultaat.

---

## 2. Number (Getallen)

5. **Basis rekenen:**
   Maak twee variabelen `getal1 = 15` en `getal2 = 4`. Bereken de som, het verschil en het product, en sla elk resultaat op in een nieuwe variabele.

6. **Restwaarde (Modulo):**
   Gebruik de modulo-operator (`%`) om de restwaarde te berekenen wanneer je `23` deelt door `5`. Print de rest.

7. **Kommagetallen:**
   Maak een variabele `prijs = 19.99` en `aantal = 3`. Bereken de totale prijs en gebruik `.toFixed(2)` om het af te ronden op twee decimalen.

8. **Increment:**
   Maak een variabele `teller = 0`. Verhoog de waarde met `1` met behulp van de `++` operator en print de nieuwe waarde.

---

## 3. Boolean (Waar / Niet waar)

9. **Vergelijking:**
   Maak variabelen `leeftijd = 18` en `minimumLeeftijd = 18`. Maak een boolean variabele `isLegaal` die controleert of `leeftijd` groter is dan of gelijk aan `minimumLeeftijd` (`>=`).

10. **Gelijkheidstest:**
    Controleer of `"5"` (string) gelijk is aan `5` (number) met behulp van strikte gelijkheid (`===`). Print de uitkomst (`true` of `false`).

11. **Boolean omdraaien:**
    Maak een variabele `isIngelogd = true`. Gebruik de NOT-operator (`!`) om een variabele `isUitgelogd` te maken met de tegenovergestelde waarde.

---

## 4. Undefined & Null

12. **Undefined ontdekken:**
    Declareer een variabele `let gebruiker;` zonder er direct een waarde aan toe te kennen. Print de variabele en bekijk het type in de console.

13. **Null toewijzen:**
    Maak een variabele `gekozenKleur = null`. Print de variabele en merk het verschil op met `undefined`.

14. **Waarde aanpassen:**
    Wijs later aan `gekozenKleur` de string `"blauw"` toe en print de variabele opnieuw.

---

## 5. Typeof (Types controleren)

15. **Type van een string:**
    Gebruik `typeof` om het type van `"123"` te controleren en print het naar de console.

16. **Type van een number:**
    Gebruik `typeof` om het type van `123` te controleren en print het naar de console.

17. **Type van een boolean:**
    Gebruik `typeof` op de waarde `true` en bekijk het resultaat.

---

## 6. Type Conversie (Omzetten van types)

18. **String naar Number:**
    Maak een variabele `tekstGetal = "42"`. Zet deze om naar een echt getal met `Number()` of `parseInt()` en tel er `8` bij op.

19. **Number naar String:**
    Maak een variabele `score = 100`. Zet deze om naar een string met `String()` of `.toString()` en plak er de tekst `" punten"` achteraan.

---

