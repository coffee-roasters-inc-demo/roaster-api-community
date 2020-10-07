![GitHub Actions badge](https://github.com/coffee-roasters-inc-demo/roaster-api-community/workflows/Azure%20Static%20Web%20Apps%20CI%2FCD/badge.svg "Status on GitHub Actions with Azure Static Web App")

# Roaster-API community edition with documentation

Welcome to <b>Roaster-API community edition</b> GitHub repository! This repository contains both Roaster APIs - community edition: programming source codes with documentation. 

Note that [documantation web page](https://salmon-coast-098ef9d00.azurestaticapps.net/) is powered by [Azure Static Web Apps](https://docs.microsoft.com/en-us/azure/static-web-apps/overview) and [GitHub Actions](https://github.com/features/actions) using [Hugo framework](https://gohugo.io/).

## Running Roaster-API locally

1. Run `dotnet run -p generator/src/generator.csproj -- . "http://localhost:8000/" _site` to build the HTML files.
2. Run `./copy-assets.bash _site` to copy assets into the target directory.
3. Run `python3 -m http.server 8000 --directory _site/` (or whatever your favorite static http server is) to serve the website at port 8000.
4. Open `http://localhost/:8000` in your web browser to view the result.

## Contribute

- Please see more details on [LICENSE](LICENSE) and [Contributing](https://salmon-coast-098ef9d00.azurestaticapps.net/) section on documentation.