# DS_K1C - personal Creality K1C stuff

## Orca Slicer configs

### [DS_K1C_04mm.orca_printer](orca/DS_K1C_04mm.orca_printer)

- Creality K1C printer profile for 0.4mm nozzle
- process settings for typical printing of:
  - 0.08mm layer
  - 0.12mm layer
  - 0.16mm layer
  - 0.20mm layer

### [Creality Generic PLA-CF.orca_filament](orca/Creality%20Generic%20PLA-CF.orca_filament)

Creality Hyper PLA-CF

---

## Other/Notes

### Conventions

- for visibility in Orca Slicer, all profiles are prefixed with `DS_`
- Orca Slicer keeps exported file name equal to profile name only for printer profile, `.orca_filament` is auto generated and kept as-is for easier dumping

### `.gitconfig`

```
[diff "zip"]
  textconv = unzip -c -a
```
