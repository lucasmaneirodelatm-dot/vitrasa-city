                    API Cloudflare
                          │
                    Central Ciudad A
                          │
     ┌──────────┬─────────┼─────────┬──────────┐
     │          │         │         │          │
   Buses     Semáforos  Paradas   Tren    Cocheras

# ARQUITECTURA

## Objetivo

Crear una ciudad inteligente en miniatura basada en VITRASA.

## Elementos

- API Cloudflare
- Central Ciudad A
- Central Ciudad B
- Buses
- Paradas
- Semáforos
- Tren
- Paso a nivel
- Cocheras
- Farolas

## Esquema

                 API Cloudflare
                        │
        ┌───────────────┴───────────────┐
        │                               │
   Central Ciudad A               Central Ciudad B
        │                               │
        ├── Buses                       ├── Buses
        ├── Paradas                     ├── Paradas
        ├── Semáforos                   ├── Semáforos
        ├── Tren                        ├── Tren
        ├── Paso a nivel                ├── Paso a nivel
        ├── Farolas                     ├── Farolas
        └── Cocheras                    └── Cocheras
