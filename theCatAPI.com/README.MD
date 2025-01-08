### Using this as a test example

Generating static HTML from an OpenAPI doc

Install the OpenAPI generator CLI tool https://openapi-generator.tech/docs/installation/

If via Homebrew:
```bash
openapi-generator generate -i https://raw.githubusercontent.com/thatapicompany/apis/main/theCatAPI.com/thecatapi-oas.yaml -g html2 -o ./the-cat-api-html-example
```

If via NPM:
```bash
npx @openapitools/openapi-generator-cli generate -i https://raw.githubusercontent.com/thatapicompany/apis/main/theCatAPI.com/thecatapi-oas.yaml -g html2 -o ./the-cat-api-html-example
```