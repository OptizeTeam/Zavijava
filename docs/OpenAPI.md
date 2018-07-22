Dokumentując API należy trzymać się reguł, które pozwolą nam na tworzenie zwięzłej, bezbłędnej, a zarazem dokładnej dokumentacji.

Podstawowym dokumentem opisującym opisującym dokumentację API jest [OpenAPI Specification](https://swagger.io/specification/). Poza bezwzględnym stosowaniem się do zawartych w nim zaleceniach, należy zwrócić uwagę na to, czy dokumentacja z naniesionymi zmianami nie zwraca żadnych błędów czy ostrzeżeń w [Swagger Editor](http://editor.swagger.io). Dodatkowe  reguły, które należy stosować przy pracy z dokumentacją OpenAPI:
1. Wcięcia powinny składać się z dwóch spacji (nie tabulatora).
2. Kod powinien być możliwie zwięzły (bez zbędnych pustych linii czy apostrofów).
3. Wszystko co możliwe powinno być rozbite na stosowne komponenty: parametry, zwrotki, schematy, etc.
4. Typy powinny być opatrzone formatem.
5. Tam gdzie to możliwe, powinien być stosowany podstawowy opis.
6. Jeśli w ramach jednego routingu kilka metod wymaga tych samych parametrów, należy je udokumentować w routingu, a nie w każdej metodzie z osoba (oszczędność kodu).
7. Na końcu pliku powinna być pusta linia.

Zalecane narzędzia do pracy z OpenAPI:
* [Swagger Editor](http://editor.swagger.io)
* Rozszerzenie [Senya Editor](https://tree.taiga.io/project/senya-dev-senya/) do produktów JetBrains
* Rozszerzenie [openapi-lint](https://marketplace.visualstudio.com/items?itemName=mermade.openapi-lint) do Microsoft Visual Studio Code