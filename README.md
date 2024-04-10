## PHP i Docker

Instruccions instal·lació:

1. Clonar el repo.
2. `cd` al directori.
3. Generar la imatge: `docker build -t php-docker .`
4. Crear i executar el contenidor: `docker run -d --rm -p 80:80 php-docker`. Podeu afegir un volum si voleu modificar els fitxers més còmodament.
5. Amb el navegador, accedir a `http://localhost`.