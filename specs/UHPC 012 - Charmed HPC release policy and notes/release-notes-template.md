# Charmed HPC <major release>.<patch version #> Release Notes

Release date: YYYY-MM-DD

## Summary

Brief overview of this release, including the primary focus (e.g., new Ubuntu base,
new artifact versions, bug fixes, security updates).

## Artifacts in this release

| Artifact | Track | Revision | Notes |
|----------|-------|----------|-------|
| Charmed Slurm | <track> | <revision> | See [Charmed Slurm release notes] |
| apptainer-operator | <track> | <revision> | |
| cephfs-server-proxy | <track> | <revision> | |
| filesystem-client | <track> | <revision> | |
| lustre-server-proxy | <track> | <revision> | |
| nfs-server-proxy | <track> | <revision> | |
| test-mount-client | <track> | <revision> | |
| lustre-server | <track> | <revision> | |
| sssd-operator | <track> | <revision> | |

## What's new

### New features

- Feature description and the artifact(s) it affects.

### Improvements

- Improvement description.

## Bug fixes

- Bug description, the artifact(s) affected, and a link to the issue.

## Security fixes

- CVE or advisory reference, the artifact(s) affected, and the severity.

## Requirements and compatibility

### Supported Ubuntu base

- Ubuntu <version> LTS (<codename>)

### Juju version

- Minimum Juju version: <version>
- Maximum Juju version: <version>

### Compatible third-party charm versions

These charms are not released by the Charmed HPC team. This release is supported only
in combination with the versions listed below.

| Charm | Channel | Revision | Required by | Notes |
|-------|---------|----------|-------------|-------|
| mysql | 8.4/stable | <revision> | slurmdbd | |
| smtp-integrator | <channel> | <revision> | slurmctld | Optional, for email notifications |

## Support matrix

| Combination | Tested | Depth of testing | Supported |
|-------------|--------|------------------|-----------|
| <artifact> on <Ubuntu base> with <Juju version> | Yes/No | Unit / integration / scale / full QA | Supported / Unsupported |

Unsupported combinations:

- Mixing artifact versions from different Charmed HPC releases.
- Ubuntu bases other than the base listed above.

## Backwards incompatible changes

- Change description and required user action, if any.

## Deprecated features

- Feature or option that is deprecated, with recommended alternative.

## Known issues

- Issue description and any available workaround.

## Upgrade notes

Only upgrades between minor versions within the same major release are supported.

### Refreshing charms

```bash
juju refresh <charm-name> --channel <track>/stable
```

## Support lifecycle

| Release | Release date | End of support |
|---------|--------------|----------------|
| <major release>.<patch version #> | YYYY-MM-DD | YYYY-MM-DD |

Bug and security fix support is tied to the Ubuntu LTS release this version is built against, and is provided under the terms of Ubuntu Pro support.

## Acknowledgements

We appreciate the contributions of the Slurm open source community, and of the
upstream communities behind the other projects Charmed HPC builds on.

## References

- [Charmed HPC release policy](link to this spec)
- [Charmed Slurm release notes](link)
