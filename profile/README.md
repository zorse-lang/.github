# Zorse Programming Language

Zorse is a programming language to create Infrastructure and Application as Code
(IA³C) for cloud environments. You can do backend, frontend, and infrastructure
with Zorse all in the same zorse code! The "3" in IA³C indicates:

- Application code for frontend (e.g. React, Vue, Angular, etc.)
- Application code for backend (e.g Express, Fastify, AWS Lambdas, etc.)
- Application code for infrastructure (e.g. AWS CDK, CDK-TF, CDK-8s, etc.)

Zorse is designed as a superset of TypeScript, and introduces the concept of how
bundling works in JavaScript, at syntax level.

Zorse also expands upon the NodeJS runtime to bring in new security features, to
meet the demands of modern DevSecOps and DevOps workflows at enterprise level.

Zorse comes with a compiler (`zorc`), a runtime (`zort`), alongside a deployment
orchestration CLI (`zord`). The agent orchestrates deployment of infrastructure.

The compiler, the runtime, and the orchestration CLI, alongside other tools and
npm are all bundled in a single static binary called `zorse`.

Applications compiled by Zorse are backwards compatible with NodeJS, however the
VM additions to harden the runtime are obviously not available if you run zorse
code outside of its own runtime.

Extension for zorse code is `.zrc`. (substitute "s" with "z" in "src").

The term "Zorse" is a real life animal, a cross between a zebra and a horse.  
<https://en.wikipedia.org/wiki/Zebroid>
