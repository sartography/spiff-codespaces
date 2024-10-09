# spiff-codespaces

hammer this inside of your github codespaces terminal:

    docker compose --file docker-compose.yml --file .devcontainer/devcontainer-docker-compose.yml up --wait

since the devcontainer.json is currently not being used.
then access the exposed port address for 8003 in the browser (8003 is the nginx container that reverse proxies requests to frontend (/) and backend (/api).
the setup doesn't quite work yet.
you get a partially-successful login and then end up back on the login page.
