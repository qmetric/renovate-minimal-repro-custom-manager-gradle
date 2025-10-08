# 38461

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate fails to create a PR to "Update all non-major dependencies".

## Expected behavior

Renovate should raise a PR to "Update all non-major dependencies". This PR should include upgrades to junit:junit and net.bytebuddy:byte-buddy from the public registry, and also org.testcontainers:testcontainers from a custom manager that's pulling the version from github releases.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/38461
