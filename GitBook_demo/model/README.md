# Model overview

The Model module is where a project's systems under test get defined before
any test case can be built against them. Every artifact created here becomes
a reusable building block in Design and Automation.

## Artifact types

- **WOR** — Web object repository
- **Mobile OR** / **Windows OR** — platform-specific object repositories
- **API** — API definitions, handled entirely server-side with no
  script or keyword-engine dependency
- **Calc (CAL)** — calculation/simulation nodes
- **PDF** — document verification nodes; only three file-config steps
  (name, path, type) are needed before verify text/image steps
- **FOR** — billing and financial-record generation across organizations
  (medical claims, purchases, and similar record types)

## Where Model fits

Model sits in the Planning phase alongside Design, Hub, and Defect. Nothing
in Design can reference an object that hasn't been defined here first.
