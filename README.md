# Projektni naziv: CDM System (Cart, Display, Manager)

## Opis projekta
Ovaj projekat implementira jednostavan sistem za upravljanje proizvodima i korpom. 
Omogućava kreiranje proizvoda, dodavanje u korpu, prikaz svih proizvoda 
i računanje ukupne vrednosti.

## Klase

### Product
- Atributi: `name`, `price`, `quantity`
- Metode:
  - `display_info()` – prikazuje informacije o proizvodu
  - `total_spent()` – izračunava ukupnu vrednost proizvoda (`price * quantity`)

### ProductManager
- Čuva listu proizvoda
- Metode:
  - `add_product(product)` – dodaje proizvod u listu
  - `display_all_products()` – prikazuje sve proizvode
  - `total_spent()` – računa ukupnu vrednost svih proizvoda

### Cart
- Čuva proizvode koje korisnik želi da kupi
- Metode:
  - `add_product(product)` – dodaje proizvod u korpu
  - `total_spent()` – računa ukupnu vrednost svih proizvoda u korpi

## Funkcionalnosti
- Kreiranje proizvoda i dodavanje u listu/korpu
- Prikaz proizvoda
- Izračunavanje ukupne vrednosti proizvoda
- Ignorisanje poverljivih fajlova (`config.json`) i snimaka ekrana putem `.gitignore`ine_sales_analysis
