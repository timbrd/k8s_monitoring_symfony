ARG VERSION

FROM mysql:${VERSION} as prod

# Copy sql dump to initialize tables on startup
COPY init /docker-entrypoint-initdb.d
