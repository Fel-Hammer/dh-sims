Vengeance Demon Hunter, Midnight 12.1.5 PTR.

`vengeance.simc` holds both hero trees as two actors, Aldrachi Reaver and Annihilator, each with its own gear and single-target talents.
Simmed at target_error 0.05.

![Every build's single-target damage against its damage in the +20 dungeon](build-comparison.svg)

## ST: 1 target, 300s, lust ([report](https://mimiron.raidbots.com/simbot/report/1j9FiHuGfo8wXRQksyJhgm))

| Build | DPS | Build report |
|---|---|---|
| aldrachi-st | 154,316 | [report](https://mimiron.raidbots.com/simbot/report/qzGgoJxLABBtEaXsoGy1r2) |
| aldrachi-aoe | 149,957 | [report](https://mimiron.raidbots.com/simbot/report/9JgTSznBtD1oM5vygD2fEx) |
| annihilator-st | 143,887 | [report](https://mimiron.raidbots.com/simbot/report/mL8nsw2ur6m8tjEb6rn6Cp) |
| annihilator-aoe | 142,039 | [report](https://mimiron.raidbots.com/simbot/report/4VghkhnQtEWvEEF6oiLGrM) |

## Cleave: 3 targets, 300s, lust ([report](https://mimiron.raidbots.com/simbot/report/w89xs8tppGFrkzMscUYafF))

| Build | DPS | Build report |
|---|---|---|
| annihilator-aoe | 314,751 | [report](https://mimiron.raidbots.com/simbot/report/4VghkhnQtEWvEEF6oiLGrM) |
| annihilator-st | 311,590 | [report](https://mimiron.raidbots.com/simbot/report/mL8nsw2ur6m8tjEb6rn6Cp) |
| aldrachi-aoe | 250,377 | [report](https://mimiron.raidbots.com/simbot/report/9JgTSznBtD1oM5vygD2fEx) |
| aldrachi-st | 245,088 | [report](https://mimiron.raidbots.com/simbot/report/qzGgoJxLABBtEaXsoGy1r2) |

## AoE: 5 targets, 300s, lust ([report](https://mimiron.raidbots.com/simbot/report/9Kbk6nrtnpkzWvmNXjhdSB))

| Build | DPS | Build report |
|---|---|---|
| annihilator-aoe | 460,663 | [report](https://mimiron.raidbots.com/simbot/report/4VghkhnQtEWvEEF6oiLGrM) |
| annihilator-st | 452,069 | [report](https://mimiron.raidbots.com/simbot/report/mL8nsw2ur6m8tjEb6rn6Cp) |
| aldrachi-aoe | 345,651 | [report](https://mimiron.raidbots.com/simbot/report/9JgTSznBtD1oM5vygD2fEx) |
| aldrachi-st | 332,916 | [report](https://mimiron.raidbots.com/simbot/report/qzGgoJxLABBtEaXsoGy1r2) |

## Dungeon: Temple of Sethraliss route, +20 keystone ([report](https://mimiron.raidbots.com/simbot/report/dGEgtLRy4yw7me95fr2xSF))

`temple-of-sethraliss-route.simc` walks a Temple of Sethraliss M+ route end to end. The pulls,
the chaining and the mob health all come off 12.1 PTR logs, scaled down to one actor, with health
at a +20 keystone. Run it with:

    simc vengeance.simc temple-of-sethraliss-route.simc

| Build | DPS | Build report |
|---|---|---|
| annihilator-st | 324,316 | [report](https://mimiron.raidbots.com/simbot/report/mL8nsw2ur6m8tjEb6rn6Cp) |
| annihilator-aoe | 321,433 | [report](https://mimiron.raidbots.com/simbot/report/4VghkhnQtEWvEEF6oiLGrM) |
| aldrachi-aoe | 296,153 | [report](https://mimiron.raidbots.com/simbot/report/9JgTSznBtD1oM5vygD2fEx) |
| aldrachi-st | 290,329 | [report](https://mimiron.raidbots.com/simbot/report/qzGgoJxLABBtEaXsoGy1r2) |

## Talent strings

| Build | Talent string | Report |
|---|---|---|
| aldrachi-st | `CUkAAAAAAAAAAAAAAAAAAAAAAAAYMzMzMMjMzMzY2MzMDYMzYGzYmZYGzMWmZGMmBAAAgZbGMMWWYCDzMjFAAAAMwAAgZGgBAAAwA` | [report](https://mimiron.raidbots.com/simbot/report/qzGgoJxLABBtEaXsoGy1r2) |
| aldrachi-aoe | `CUkAAAAAAAAAAAAAAAAAAAAAAAAYMzMzMMjMzMzY2MzMzMYMzYGzYGDzwMWmZGMmBAAAgZZGMM2WYCDzMjFAAAAMwAAgZGgBAAAwA` | [report](https://mimiron.raidbots.com/simbot/report/9JgTSznBtD1oM5vygD2fEx) |
| annihilator-st | `CUkAAAAAAAAAAAAAAAAAAAAAAAAYMzMPwMzMjMzMzM2MzMDYMzYGzYmZYGzM2mZmtxAAAAAAAABMzM2AAAAwAmZmZWabmZGAMAAAAMA` | [report](https://mimiron.raidbots.com/simbot/report/mL8nsw2ur6m8tjEb6rn6Cp) |
| annihilator-aoe | `CUkAAAAAAAAAAAAAAAAAAAAAAAAYMzMPwMzMjMzMDzmZmZmBjZGzYGzYYGzM2mZmtxAAAAAAAABMzM2AAAAwAmZmZWabmZGAMAAAAMA` | [report](https://mimiron.raidbots.com/simbot/report/4VghkhnQtEWvEEF6oiLGrM) |

## Contributing

PRs welcome! If you beat one of these numbers include the profile changes and a Raidbots report at target_error 0.05.
