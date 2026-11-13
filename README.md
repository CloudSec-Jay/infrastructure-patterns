# Infrastructure patterns

Public collection for reusable infrastructure extracted from a private cloud
orchestration platform. Each pattern must pass the publication checklist before
it is presented as production-ready.

## Collections

- `cloudformation/`: focused AWS templates and nested-stack patterns
- `ansible/`: reusable roles, collections, and platform automation patterns
- `terraform/`: small AWS modules and composition examples

Live environments, inventories, account identifiers, operational evidence,
workload-specific configuration, credentials, state, and generated output do
not belong here.

## Promotion model

The private orchestration repository remains the source of truth. A pattern is
copied here only after its interface is generalized, examples are sanitized,
tests are added, and ownership and licensing are explicit. Public releases are
intentional snapshots, not automatic mirrors of the private platform.

## License

Apache License 2.0. See [`LICENSE`](LICENSE).
