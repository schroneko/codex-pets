# Codex Pets

Private collection of Codex pet assets.

## Pets

- `nuko`: ぬこぬこ
- `nukoevi`: ぬこエビちゃん

## Install

Clone this private repository with an account that has access, then copy a pet directory into `~/.codex/pets`.

```sh
gh repo clone schroneko/codex-pets
mkdir -p ~/.codex/pets
cp -R codex-pets/pets/nuko ~/.codex/pets/nuko
cp -R codex-pets/pets/nukoevi ~/.codex/pets/nukoevi
```

## Layout

```text
pets/
  nuko/
    pet.json
    spritesheet.webp
  nukoevi/
    pet.json
    spritesheet.webp
```

Each pet directory contains the runtime files: `pet.json` and `spritesheet.webp`.
