# Com llançar l'aplicació amb un Servidor Local

Aquesta aplicació guarda dades al navegador. Perquè funcioni correctament i no es perdin les dades en fer F5 (especialment en Chrome/Edge), es recomana executar-la mitjançant un servidor local en lloc d'obrir el fitxer directament.

## Instruccions

1. Assegura't de tenir **Node.js** instal·lat.
2. Obre una terminal a la carpeta del projecte.
3. Executa la següent ordre per instal·lar i llançar el servidor:
   ```bash
   npm start
   ```
4. L'aplicació s'obrirà automàticament a `http://localhost:8080`.

Si no tens Node.js, també pots utilitzar Python:
```bash
python -m http.server 8080
```
A continuació, obre el navegador a `http://localhost:8080`.
