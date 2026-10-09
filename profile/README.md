# Impact Gate

Impact Gate is a warn-only pull request gate. When an API contract (OpenAPI) changes, it reports which consuming services and call sites that change can affect. It warns; it does not block merges.

**Status: early.** Prototype with synthetic and demo evidence only. No production customers yet.

## Start here

- **Website and live demo:** [impactgate.in](https://impactgate.in)
- **See it on a real PR:** [ig-lab-petclinic](https://github.com/impact-gate/ig-lab-petclinic) is a Spring PetClinic REST fork with open demo PRs that change the OpenAPI contract. Its consumers are [consumer-1](https://github.com/impact-gate/ig-lab-petclinic-consumer-1), [consumer-2](https://github.com/impact-gate/ig-lab-petclinic-consumer-2) and [consumer-3](https://github.com/impact-gate/ig-lab-petclinic-consumer-3).
- **Run the benchmark yourself:** [impact-gate-benchmarks](https://github.com/impact-gate/impact-gate-benchmarks) has 13 labelled OpenAPI cases, a scorer and an oasdiff reference run. MIT licensed.

## Get involved

- Think a benchmark label is wrong, or have a case we should add? [Open an issue](https://github.com/impact-gate/impact-gate-benchmarks/issues).
- Want to try it on your own APIs? Say hello at [impactgate.in](https://impactgate.in).

Other `ig-lab-*` repositories are test fixtures for the gate, not products. Forks of Strapi and Fastify are kept for benchmark work.

[LinkedIn](https://www.linkedin.com/company/impactgate-in) | [Instagram](https://www.instagram.com/impactgate/)
