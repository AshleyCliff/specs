# Charmed HPC <major>.<minor> Release Notes

Release date: YYYY-MM-DD

## Summary

Release type: Major release / Minor feature update / Bug or security patch

<Brief overview of this release, including the primary focus (e.g., new Ubuntu base,
new upstream releases such as Slurm or Lustre, new features, bug fixes, security updates).>

## Artifacts in this release

| Artifact | Track | Revision | Notes |
|----------|-------|----------|-------|
| slurmctld | <track> | <revision> | |
| slurmd | <track> | <revision> | |
| slurmdbd | <track> | <revision> | |
| sackd | <track> | <revision> | |
| slurmrestd | <track> | <revision> | |
| apptainer-operator | <track> | <revision> | |
| cephfs-server-proxy | <track> | <revision> | |
| filesystem-client | <track> | <revision> | |
| lustre-server-proxy | <track> | <revision> | |
| nfs-server-proxy | <track> | <revision> | |
| lustre-server | <track> | <revision> | |
| sssd-operator | <track> | <revision> | |
| openssh-operator | <track> | <revision> | |

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

This release is supported only on the Ubuntu base and Juju versions listed below, and
only with the artifact and third-party charm versions listed in these release notes.
Compatibility is only guaranteed between charm revisions from this release
(<major>.<minor>). Mixing revisions from any other release, including other minor
releases of the same major release, is not supported.

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
| cos-lite | <channel> | <revision> | slurmctld | Observability via cos-agent; Kubernetes; cross-model |
| authentik-server | <channel> | <revision> | sssd | Optional, for identity; Kubernetes; cross-model |
| smtp-integrator | <channel> | <revision> | slurmctld | Optional, for email notifications |


## Breaking changes

Major releases only; breaking changes are not made in minor releases.

- Change description and required user action, if any.

## Deprecated features

- Feature or option that is deprecated, with recommended alternative and anticipated removal date.

## Known issues

- Issue description and any available workaround.

<!--## Upgrade notes

Only upgrades between minor versions within the same major release are supported.
All charms must be refreshed to this release; mixing revisions from different releases
is not supported.

## Support lifecycle

| Release | Release date | End of support |
|---------|--------------|----------------|
| <major>.<minor> | YYYY-MM-DD | YYYY-MM-DD |

Bug and security fix support is tied to the Ubuntu LTS release this version is built against, and is provided under the terms of Ubuntu Pro support.
-->
## Acknowledgements

<Acknowledge contributions for upstream contributions to artifacts (Slurm, Lustre, etc.)>

## References

- [Charmed HPC release policy](link to this spec)
- [Charmed HPC Risk Gate policy]()
