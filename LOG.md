# LOG

Aquest document recull els canvis del projecte.

## Exercici dels tags

- Canvis: tres rutes per gestionar els tags, validació del body, funcions al controller i al service, i documentació a Swagger.
- Les respostes retornen el llibre actualitzat amb els autors. Afegir un tag repetit o treure un tag que no hi és no dona error.
- Comprovacions: `npm run build` i `npm run lint` correctes. També han passat 19 peticions amb la base de dades simulada i la comprovació de les rutes de Swagger.
- Falta provar-ho amb MongoDB real: l’executable instal·lat es tanca sense arrencar la base de dades de prova.
