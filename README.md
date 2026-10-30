# troi-runner-builds

Builds of third-party programs that the Troi Runner downloads when their
publishers do not ship one for a CPU (today: Windows ARM64).

- One release per program version, e.g. `jackett-v0.24.1957`.
- Each file is pinned by SHA256 in the Runner's dependency registry, so a
  file here is never replaced; a new build is a new release.
- Each release names the exact upstream source (tag and commit) and the
  build script used. The programs keep their own licenses; each archive
  carries its upstream license file.
