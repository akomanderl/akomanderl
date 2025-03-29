# Logistics Simulator 3D

Symulator przepływów logistycznych z wykorzystaniem urządzeń automatycznego transportu wewnętrznego, zbudowany na silniku Godot 4 z wykorzystaniem języka C#.

## Funkcje projektu

- Modelowanie przepływu materiałów w 3D
- Przyspieszona symulacja czasu (np. 1 godzina w 10 minut)
- Testowanie logiki sterowania i optymalizacji

## Wymagania

- Godot 4.x Mono
- .NET SDK 6.x lub 7.x
- Visual Studio 2022 lub VS Code z wtyczką C#

## Dokumentacja

- [Konfiguracja Środowiska Deweloperskiego](docs/Srodowisko_Deweloperskie.md)

## Struktura projektu

```
project/
├── project.godot
├── default_env.tres
├── main/
│   ├── Main.tscn
│   └── Main.cs
├── scripts/
│   └── README.md
└── assets/
    └── .gitkeep
```

## Uruchomienie projektu

1. Skonfiguruj środowisko zgodnie z dokumentacją.
2. Otwórz folder `project` w Godot.
3. Uruchom scenę `main/Main.tscn`.
