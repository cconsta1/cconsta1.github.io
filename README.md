# Academic Research Website

Source for the personal academic website of Chrysovalantis Constantinou.

This site is built with Jekyll and is based on the Academic Pages / Minimal Mistakes ecosystem, tailored to a strictly academic structure (About, Publications, Talks, CV) and configured with `jekyll-seo-tag` for academic-grade metadata.

## Local preview

Install Ruby + Bundler, then:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

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
