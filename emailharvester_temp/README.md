# Docker - EmailHarvester

A Dockerized version of the tool EmailHarvester by maldevel

## Building the image

```docker build -t emailharvester .```

## Running the container

```docker run -it emailharvester <target>```

## Troubleshooting

```docker run -it emailharvester <target> -r dogpile```

If you get "Connection Aborted." error exclude dogpile plugin
