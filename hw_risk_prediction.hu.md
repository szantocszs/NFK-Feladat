# Cukorbetegség kockázatának előrejelzése

## Összefoglaló

Ennek a feladatnak a célja a `sklearn.datasets` csomagban található **diabetes** adatállomány (`load_diabetes`) felhasználása egy bináris osztályozó modell létrehozásához, amely a célváltozó alapján előrejelzi, hogy egy páciens **veszélyeztetett-e** a cukorbetegség szempontjából.

A feladat a következő lépésekből áll:

* Az adathalmaz előfeldolgozása, valamint két küszöbérték (150 és 250) meghatározása a páciensek „Veszélyeztetett” és „Nem veszélyeztetett” kategóriákba sorolásához.
* Egy gépi tanulási modell betanítása és kiértékelése bináris osztályozási feladatra.
* Vizualizációk készítése az adatok eloszlásának és a modell teljesítményének értékeléséhez.

**Megjegyzés:** A hangsúly egy robusztus modell felépítésén és az eredmények értelmezését segítő, jól áttekinthető vizualizációk készítésén van.

## Feladat

* Az adathalmaz betöltése a következő módon:  
  `diabetes = load_diabetes(scaled=False)`  
  Dokumentáció: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

* Az adathalmaz feltérképezése, valamint a jellemzők (feature-ök) és a célváltozó összefoglalása.

* Két különböző forgatókönyv definiálása a célváltozóra (utolsó oszlop) alkalmazott eltérő küszöbértékekkel:
  - **1. forgatókönyv:** Azok a páciensek, akiknek a célértéke 150 felett van, „Veszélyeztetett” kategóriába kerülnek, míg az ez alattiak „Nem veszélyeztetett”-nek számítanak.
  - **2. forgatókönyv:** Azok a páciensek, akiknek a célértéke 250 felett van, „Veszélyeztetett”-nek minősülnek, míg az ez alattiak „Nem veszélyeztetett”-nek számítanak.

* Bináris osztályozó modell felépítése mindkét forgatókönyvre, valamint az eredmények megvitatása, beleértve:
  - a modell(ek) teljesítményét,
  - az alkalmazott modelleket,
  - az értékelési módszereket,
  - és a levont következtetéseket.

## Leadandó anyagok

* Egy Python szkript vagy Jupyter Notebook, amely tartalmazza:
  - az adatelőkészítést,
  - a modell tanítását,
  - az értékelést,
  - valamint a vizualizációkat.

* Egy rövid beszámoló az eredményekről, amely tartalmazza:
  - az adatelemzés eredményeit,
  - a modell teljesítménymutatóit,
  - a vizualizációkat és azok értelmezését.