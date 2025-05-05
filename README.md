# Demo CI/CD con Postman y Newman

Este repositorio contiene una colección Postman de ejemplo y una integración con GitHub Actions para ejecutar pruebas automatizadas con Newman.

## ¿Qué contiene?
- Carpeta `postman/` con una colección de ejemplo (`GET /posts/1`).
- Pipeline de GitHub Actions que ejecuta Newman al hacer push o pull request.

## ¿Cómo usarlo?
1. Sube este repositorio a GitHub.
2. Asegúrate de tener una rama `main`.
3. Ve a la pestaña de 'Actions' en tu repo.
4. Verás que se ejecutan automáticamente las pruebas.

## Requisitos
- Tener configurado GitHub Actions (viene habilitado por defecto).
- Node.js y Newman se instalan automáticamente durante la ejecución.
