# Academic Research Website

Source for the personal academic website of Chrysovalantis Constantinou.

This site is built with Jekyll and is based on the Academic Pages / Minimal Mistakes ecosystem, tailored to a strictly academic structure (About, Publications, Talks, CV) and configured with `jekyll-seo-tag` for academic-grade metadata.

## Local preview

The easiest way on a Mac is Docker (see the Docker section below): start Docker Desktop, run `docker compose up --build`, and open `http://localhost:4000`.

To run natively instead, use Ruby 3.2 (the version the GitHub Actions build uses; macOS system Ruby is too old), e.g. via `rbenv`, then:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`. Restart the server after editing `_config.yml`.

## Reuse

If you want to reuse this as a starting point, fork the repository and update:

- Site metadata in `_config.yml`
- Navigation in `_data/navigation.yml`
- Content pages in `_pages/`
- Your CV PDF in `files/`

Upstream theme documentation is available from the Academic Pages project.

## Docker (optional)

This repository includes a `Dockerfile` and `docker-compose.yaml` to run the site inside a container. To build and serve the site with Docker Compose:

```bash
docker compose up --build
```

The site will be served at `http://localhost:4000`. To stop the container:

```bash
docker compose down
```

Use `docker compose up` without `--build` if the image is already built and you only want to start the container.
