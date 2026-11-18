# appshell_navbar_gradient (bug repro)

.NET MAUI reproduction showing that a linear-gradient background set via a custom
`ShellRenderer`/`IShellToolbarAppearanceTracker` on the Android Shell navigation
bar is not applied (regression from Xamarin.Forms).

## Target framework

`net10.0-android`

## Build

```bash
dotnet build navbar/navbar.csproj -f net10.0-android
```
