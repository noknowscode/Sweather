# Worn

Weather by wardrobe: instead of a forecast, the app tells you what to wear, with a daily outfit memo, an hourly wardrobe strip and city search.

## What's inside

- **Custom controls:** `ClotheslineCard`, `DayCard`, `HeadlineTicker`.

## Built with

- Uno Platform single project, `Uno.Sdk` 6.5.29 (pinned in `global.json`).
- Targets: Android, WebAssembly, Desktop (net10.0).
- Material theme, SVG, Hosting and dependency injection, Uno Toolkit, MVUX, Skia renderer.

## Run it

You need the .NET 10 SDK. Run `uno-check` first on a fresh machine.

```bash
dotnet run --project Worn/Worn.csproj -f net10.0-desktop
```

## Design docs

- [`worn-spec-kit.md`](worn-spec-kit.md)
- [`worn-uno-mapped-spec-kit.md`](worn-uno-mapped-spec-kit.md)

## License

MIT. See [LICENSE](LICENSE).
