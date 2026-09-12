# Notes

## Flows
1. Development flow
  2. Edit
  3. `make -j$(nproc)`
  4. Test via new .gba file
  5. Re-edit
2. Deployment flow (.gba)
  1. `make tidyrelease`
  2. `make release -j$(nproc)`
3. Deployment flow (.bps)
  1. `make tidyrelease`
  2. `make patch [PATCH_NAME=patch-name.bps] -j$(nproc)`

## Practice
build unmodified expansion → change a Pokémon → change a trainer → change wild encounters → edit a map in Porymap → create NPC dialogue → create a scripted event → add a custom map → add a custom Pokémon/item/move → modify C code → implement an entirely new mechanic.
