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
