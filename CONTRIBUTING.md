# Contributing Guidelines

Dzięki za chęć współtworzenia projektu 🚀

To repozytorium służy przede wszystkim nauce:
- pracy zespołowej,
- korzystania z Git i GitHub,
- tworzenia czytelnego kodu,
- współpracy podobnej do tej w realnych zespołach developerskich.

---

# Jak pracujemy

## 1. Każda funkcjonalność = osobny branch

Nie pracujemy bezpośrednio na `main`.

### Schemat branchy

```txt
feature/nazwa-funkcji
bugfix/opis-błędu
refactor/nazwa-refaktoru
```

### Przykłady

```txt
feature/user-auth
bugfix/navbar-mobile
refactor/api-service
```

---

## 2. Rób małe i logiczne commity

Jeden commit powinien opisywać jedną zmianę.

### ✅ Dobre przykłady

```bash
git commit -m "Add login form validation"
git commit -m "Fix responsive sidebar layout"
git commit -m "Refactor API request handling"
```

### ❌ Złe przykłady

```bash
git commit -m "fix"
git commit -m "changes"
git commit -m "final version"
```

---

## 3. Pull Request powinien być czytelny

Każdy Pull Request powinien zawierać:
- krótki opis zmian,
- informację co zostało dodane/poprawione,
- instrukcję testowania (jeśli potrzebna).

Skorzystaj z szablonu, jeśli nie masz pomysłu jak stworzyć własny.

---

## 4. Zanim wyślesz zmiany

Upewnij się, że:
- projekt się uruchamia,
- build przechodzi poprawnie,
- nie commitujesz zbędnych plików,
- kod jest sformatowany zgodnie z ustaleniami projektu.

---

## 5. Dbaj o czytelność kodu

Preferujemy:
- proste rozwiązania,
- czytelne nazwy zmiennych i funkcji,
- małe komponenty i funkcje,
- unikanie duplikacji kodu.

---

## 6. Nie wrzucaj ogromnych Pull Requestów

Małe PR-y:
- łatwiej sprawdzić,
- łatwiej testować,
- łatwiej poprawić.

Jeśli funkcjonalność jest duża — podziel ją na mniejsze części.

---

## 7. Dokumentuj ważniejsze zmiany

Dodaj krótkie wyjaśnienie jeśli:
- zmieniasz strukturę projektu,
- dodajesz nowe zależności,
- zmieniasz sposób działania aplikacji,
- dodajesz nowe endpointy lub moduły.

---

## 8. Używaj spójnego stylu kodu

Jeśli projekt posiada:
- ESLint,
- Prettier

to korzystaj z nich przed wysłaniem zmian.

---

# Workflow pracy

```txt
1. Fork / clone repo
2. Stwórz branch
3. Wprowadź zmiany
4. Commituj zmiany
5. Push branch
6. Otwórz Pull Request
7. Wprowadź poprawki po review
8. Merge 
```

---

# Cel projektu

Projekt ma pomóc w nauce:
- Git workflow,
- pracy zespołowej,
- organizacji kodu,
- code review,
- współpracy nad większym projektem.

Liczy się nie tylko efekt końcowy, ale też sposób pracy nad projektem.
