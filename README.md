# @kadena bundle

This folder ships with every **KDA-Community** release. It contains:

- **bin/kda** - a small CLI for secrets and vault, plus environment checks
- **docs/DISAMBIGUATION.md** - what's active vs defunct in the Kadena ecosystem
- **sot/** - reference material for the Source Of Truth
- **network/** - current endpoints and peers
- **secrets/** - a stub .env.example you can copy

## Quick start

    ./bin/kda info       # what is this
    ./bin/kda doctor     # is my system ready
    ./bin/kda secrets init myapp
    ./bin/kda secrets set myapp API_KEY
    ./bin/kda secrets render myapp

## If you don't need secrets

Nothing else depends on secrets/. Delete the folder if you like -
the rest of the bundle still works.

## Support

Maintained by KDA-Community. Open an issue in the releases repo that
shipped this bundle.
