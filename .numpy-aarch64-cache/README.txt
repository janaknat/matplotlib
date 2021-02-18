This folder holds the numpy=1.16 aarch64 wheels.

Building matplotlib wheels under emulation with a numpy==1.16 dependency will build numpy, costing ~45 minutes in the CI.

Prevent that by stashing numpy wheels here.
