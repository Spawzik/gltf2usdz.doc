# gltf2usdz.online

This is the source code for [gltf2usdz.online](https://gltf2usdz.online), a web app that converts glTF/glb files to USDZ. It was created to provide a simple way to convert glTF files to USDZ for use in AR Quick Look on iOS.

It is preferable to develop inside a devcontainer so you don't have to install [usd_from_gltf](https://github.com/google/usd_from_gltf) on your local machine. So, this project has a `devcontainer.json` file and you can open it in Visual Studio Code and click on "Reopen in Container" to start developing.

Made with:
- [bun](https://bun.sh)
- [react](https://reactjs.org)
- [google/usd_from_gltf](https://github.com/google/usd_from_gltf)

Acknowledgments:
- [marlon360](https://github.com/marlon360) for providing the [docker image for usd_from_gltf](https://hub.docker.com/r/marlon360/usd-from-gltf).
- [shadcn/ui](https://ui.shadcn.com) and [aceternity UI](https://ui.aceternity.com) for providing beautiful UI components.

## Development

To install the dependencies, run:

```bash
bun install
```

To start the server, navigate to the **server** directory and run:

```bash
bun run dev
```

For frontend development, navigate to the **client** directory and run:

```bash
bun run dev
```

## Deploy

There's a Docker image for the project available at [Docker Hub](https://hub.docker.com/r/arthurrmp/gltf2usdz-online). You can deploy it to your favorite cloud provider or use the Dockerfile to build your own image.
