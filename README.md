# Marketplace Intern

O aplicație web de tip marketplace intern, modernă și intuitivă, conectată la o bază de date Supabase, concepută pentru gestionarea și publicarea rapidă a anunțurilor (case, vehicule, servicii și bunuri).

## Link de Testare
Poți testa aplicația direct aici: 
[https://lttlmario.github.io/marketplace-legal/](https://lttlmario.github.io/marketplace-legal/)

## Caracteristici Principale
* **Adăugare Anunțuri:** Formular complet pentru introducerea detaliilor de contact, tipului de acțiune (Vânzare / Cumpărare), categoriei, listei de produse, prețului și a opțiunii de imagine URL.
* **Afișare Modernă (Grid View):** Carduri interactive cu design modern (Dark UI), care afișază detaliile vânzătorului, numărul de telefon, badge-uri colorate pentru categorie și acțiune, precum și link-ul și vizualizarea imaginii atașate imediat sub produse.
* **Filtrare Dinamică:** Posibilitatea de a filtra anunțurile în funcție de categorie (`CASE`, `VEHICULE`, `SERVICII`, `BUNURI`) sau de a le vizualiza pe toate simultan.
* **Formatare Automatizată a Prețului:** Detectare inteligentă a sumelor și adăugare automată a formatului monetar.

## Tehnologii Utilizate
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Design & UI:** Interfață personalizată inspirată din panouri de control moderne, optimizată pentru desktop și dispozitive mobile.
* **Bază de date & Backend:** [Supabase](https://supabase.com) (Client JS v2)

## Structura Bazei de Date (Supabase)
Tabelul `marketplace` conține următoarele coloane:
* `id` (int8, Primary Key)
* `created_at` (timestamptz)
* `nume` (text)
* `telefon` (text)
* `produse` (text)
* `imagine_url` (text)
* `pret` (text)
* `categorie` (text)
* `tip_actiune` (text)
