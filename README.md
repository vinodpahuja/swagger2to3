# Swagger2to3

A lightweight, static HTML reference page that visualizes the differences between Swagger 2.0 and OpenAPI 3.0 specification structures.

This repository is designed as a quick cheat sheet for developers working with API specs and migrating from Swagger 2 to OpenAPI 3.

## What this project does

The site compares the main sections of both API specification versions side-by-side, including:

- `info`
- `servers` vs `host` / `basePath` / `schemes`
- `paths`
- `security`
- `tags`
- `externalDocs`
- `components` vs `definitions` / `parameters` / `responses`

It is especially useful when learning the mapping between Swagger 2 and OpenAPI 3 terminology.

## Live demo

The project is published as a GitHub Pages site:

- https://vinodpahuja.github.io/swagger2to3/

## Local usage

Since this project is a simple static page, there is no build step or dependency installation required.

1. Clone the repository:
   ```bash
   git clone https://github.com/vinodpahuja/swagger2to3.git
   cd swagger2to3
   ```
2. Open `index.html` in a browser, or serve the folder with a simple local web server:
   ```bash
   python -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser.

## Repository structure

```text
swagger2to3/
├── index.html
└── README.md
```

## Notes

- The project is intentionally minimal and dependency-free.
- It is best suited for quick reference, learning, and migration planning.
- The repository currently contains a single static page rather than a larger application.

## License

This project does not currently declare a license in the repository metadata.

## Author

- Vinod Pahuja
