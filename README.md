# NGP-NamingConvention

File naming convention of the National Gallery Prague (NGP) for the photographic documentation of
collection objects, together with the institution policy that the convention needs.

This repository is a machine export from the internal source, cleaned of internal metadata (references to
internal questions, decisions and tasks, version history and open items). Do not edit the files here:
changes are made in the source and exported again.

## Files

| File | Version | Content |
|---|---|---|
| `CONVENTION.yaml` | 2.3.1 | Canonical machine-readable definition of the file naming convention used at the National Gallery Prague (NGP) for photographic documentation of collection objects. It describes file naming only and works without any pipeline. |
| `POLICY.yaml` | 1.12.0 | Settings by which applications or a pipeline process the files named by the convention, with the values chosen by NGP. Another institution may set them differently. |

## Convention and policy

The convention says how a file is named: the relation between a work and its digital representations and
the properties of each representation. It does not depend on any pipeline.

The policy is a set of settings by which other applications or a pipeline work with the files named by
the convention (what is generated, from which source, with which parameters). It defines the properties
that the convention describes and a pipeline produces, so it is needed to adopt the convention. Another
institution keeps the convention and sets its own policy.

An adaptation guide that describes the relation between the convention and the policy in detail is
planned and not yet written.

## Left out of the export

Sections that describe only the internal setup of NGP:

- `CONVENTION.yaml`: `structural_files.input_level`, `collections`
- `POLICY.yaml`: `pipeline_2_1`, `storage`, `iiif`, `package`

## Authors

- David Stecker
- Jiří Melzmuf
- Tereza Kostrounová

## License

© 2026 Národní galerie Praha (National Gallery Prague). Licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); the full text is in `LICENSE`.

Source commit of this export: `5ea3c80`.
