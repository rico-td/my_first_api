# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

`POST /additem`: Erstellt ein neues Element

`DELETE /deleteitembyid/{itemid}`: Löscht ein Element anhand seiner ID.
**Parameter**: `itemid` - Einzigartige Id des Elements

`PUT /updateitembyid/{itemId}`: aktuallisiert ein Element anhand seiner ID.
**Parameter**: `itemid` - Einzigartige Id des Elements



<!-- GET /users
Beschreibung: Ruft eine Liste aller Benutzer ab.
Beispiel-URL: https://api.example.com/users

GET /users/{userId}
Beschreibung: Ruft Informationen zu einem bestimmten Benutzer anhand seiner ID ab.
Beispiel-URL: https://api.example.com/users/123

POST /users
Beschreibung: Erstellt einen neuen Benutzer.
Beispiel-URL: https://api.example.com/users

PUT /users/{userId}
Beschreibung: Aktualisiert die Informationen eines bestimmten Benutzers.
Beispiel-URL: https://api.example.com/users/123

DELETE /users/{userId}
Beschreibung: Löscht einen bestimmten Benutzer anhand seiner ID.
Beispiel-URL: https://api.example.com/users/123

GET /products
Beschreibung: Ruft eine Liste aller Produkte ab.
Beispiel-URL: https://api.example.com/products

GET /products/{productId}
Beschreibung: Ruft Informationen zu einem bestimmten Produkt anhand seiner ID ab.
Beispiel-URL: https://api.example.com/products/456

POST /products
Beschreibung: Erstellt ein neues Produkt.
Beispiel-URL: https://api.example.com/products

PUT /products/{productId}
Beschreibung: Aktualisiert die Informationen eines bestimmten Produkts.
Beispiel-URL: https://api.example.com/products/456

DELETE /products/{productId}
Beschreibung: Löscht ein bestimmtes Produkt anhand seiner ID.
Beispiel-URL: https://api.example.com/products/456 -->
