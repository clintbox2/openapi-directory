cd compactpc-openapi-directory
echo "# CompactPC Products API

This repository provides the OpenAPI specification and Postman collection
for the CompactPC Products API.

## Files
- swagger.json → OpenAPI 3.0 spec
- openapi.yaml → API metadata for APIs.guru
- postman_collection.json → Postman collection for testing

## Base URL
https://www.compactpc.com.tw/api/v1

### Endpoints
- GET /products.json → Product list
- GET /product/{id}.json → Single product details

## Contact
info@compactpc.com.tw
" > README.md

git add README.md
git commit -m "Add README.md"
git push origin main
