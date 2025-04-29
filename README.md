# cbix-alpine

[![Build Status](https://ci.cbix.de/api/badges/cbix/apkbuilds/status.svg)](https://ci.cbix.de/cbix/apkbuilds)

Small collection of Alpine Linux packages. I'm mostly adding APKBUILDs I need in the context of creating
lightweight Docker images. Find an example Dockerfile [here](https://github.com/cbix/docker-jamserver/blob/master/jamulus/Dockerfile).
Because abuild detects runtime dependencies automatically, the resulting image only contains the necessary binaries.
