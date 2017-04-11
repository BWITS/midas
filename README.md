# midas
a small script to trigger buildkite build job.

### Who is Midas

The most famous King Midas is popularly remembered in Greek mythology for his ability to turn everything he touched into gold.

### Install

```bash
# Update Homebrew.
$ brew update

# Install the Homebrew tap.
$ brew tap bwits/extra git@github.com:BWITS/homebrew-extra.git

# List installed taps.
$ brew tap
...
bwits/extra
...

# Install Homebrew formula.
$ brew install midas
```

### Updating

When an update is made available it can be applied by the following steps:

```bash
# Always check for new Homebrew references.
$ brew update

# Upgrade Taxonline CLI when there is an update.
$ brew upgrade midas
```

### Usage

```bash
$ midas
```

### Initial Setup

1) set your develop environment in ~/.midas/config"
such as:
```
organization=example
environment=dev
buildkite_api_token=xxxxxxxxxxxxxxx
```
2) make sure you already committed and pushed the changes
3) make sure you run the tool in the right repository and branch
4) make sure pipeline name is same as repository name
