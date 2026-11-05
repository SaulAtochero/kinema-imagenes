# kinema-imagenes

Imágenes de ejercicios (estilo neón) que descarga la app Android **Kinema**.

- `manifest.json`: versión e índice de lotes (hash SHA-256 de cada ZIP y de cada imagen).
- `lotes/lote_NN.zip`: las imágenes de cada lote, que es lo que descarga la app.
- `imagenes/`: las mismas imágenes sueltas (`<id>_0.jpg`, `<id>_1.jpg`).

Se generan con `tools_pruebas/imagenes_neon/publicar.py` del repo de Kinema. La app comprueba el
manifest al arrancar y una vez al día, y solo descarga los lotes que han cambiado.

**Todos los derechos reservados.** Ver [LICENSE](LICENSE).
