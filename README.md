# Docker
In your wordpress folder, you have:

Dockerfile: instructions to build the WordPress container.

docker-compose.yml: config to run WordPress + database together.

uploads.ini: PHP settings file (e.g., for upload size limits).

Why use Docker for WordPress?
Easy to set up and replicate the environment anywhere.

Keeps WordPress and its database isolated inside containers.

Makes development, testing, and deployment consistent.

You can run the exact same setup on your laptop, on servers, or in the cloud.

A WordPress Docker project typically includes:

A Dockerfile that describes how to build a custom WordPress container image.

A docker-compose.yml file that defines how to run WordPress along with required services like a MySQL or MariaDB database container.

Sometimes extra config files like uploads.ini to customize PHP settings.
