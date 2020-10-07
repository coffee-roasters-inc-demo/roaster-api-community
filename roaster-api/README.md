# Roaster-API community edition

This is the source code for Roaster APIs - community edition!

## Running locally

1. Run `dotnet run -p generator/src/generator.csproj -- . "http://localhost:8000/" _site` to build the HTML files.
2. Run `./copy-assets.bash _site` to copy assets into the target directory.
3. Run `python3 -m http.server 8000 --directory _site/` (or whatever your favorite static http server is) to serve the website at port 8000.
4. Open `http://localhost/:8000` in your web browser to view the result.
