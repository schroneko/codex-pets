# Codex Pets

Private collection of Codex pet assets.

## Pets

- `nuko`: ぬこぬこ

## Install

Clone this private repository with an account that has access, then copy a pet directory into `~/.codex/pets`.

```sh
gh repo clone schroneko/codex-pets
mkdir -p ~/.codex/pets
cp -R codex-pets/pets/nuko ~/.codex/pets/nuko
```

## Layout

```text
pets/
  nuko/
    pet.json
    spritesheet.webp
pets.json
```

`pet.json` and `spritesheet.webp` are the runtime files. `pets.json` is a small catalog for managing multiple characters in this repository.
