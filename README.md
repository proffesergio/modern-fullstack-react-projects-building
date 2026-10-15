# Full-Stack Modern React and Next.js Application Development

An iLearnNation course for mixed self-directed learners.

**Start with [getting-started.md](getting-started.md).** Your first ten minutes
are for understanding the course, checking prerequisites, and finding your path.

Status: **original draft 0.1.0**, with a versioned [manifest](course.json), eight
focused authored chapters, and dependency-free JavaScript checkpoints. The draft
is not a published course or evidence of learner mastery. React/Next.js project
extensions require the explicitly declared framework environment; Node checkpoints
alone do not create a full-stack application.

| Order | Chapter | Practice |
| --- | --- | --- |
| 1 | [Foundations](chapters/foundations.md) | Run, edit, check, reset; first component |
| 2 | [JavaScript and TypeScript](chapters/javascript-typescript.md) | Immutable transformations and runtime checks |
| 3 | [React components](chapters/react-components.md) | State transitions, events, and labeled forms |
| 4 | [Next.js routing](chapters/nextjs-routing.md) | Routes, layouts, server/client boundaries |
| 5 | [Data and forms](chapters/data-and-forms.md) | Validated writes, identity, and persistence |
| 6 | [Quality and accessibility](chapters/quality-accessibility-security.md) | Tests, keyboard review, safe links |
| 7 | [Production workflows](chapters/production-workflows.md) | Local Git, CI proposals, rollback |
| 8 | [Capstone](chapters/capstone.md) | Private learning notebook and evidence review |

Every chapter includes objectives, prerequisites, effort, an original explanation,
a runnable checkpoint, exercise, progressive hints, reset instructions, validation,
common mistakes, accessibility notes, reflection, and references. Native disclosure
hints and static diagrams work in GitHub Markdown. Each chapter also has an optional,
collapsed, decorative GIF that plays once for 2.4 seconds; the static route and
equivalent text remain visible by default. GitHub cannot apply OS reduced-motion
settings to GIFs, and may load them before a disclosure opens. No animation is
needed to learn or complete a checkpoint. See [asset details](assets/README.md).

From the **platform repository root**, check the trusted authored examples and
manifest with Node.js 24 LTS:

```sh
node --test tests/course-schema.test.mjs tests/course-content.test.mjs
```

Those test paths belong to the platform monorepo, not a standalone published course.
You can also copy each chapter's single JavaScript checkpoint to `checkpoint.mjs`
in a practice folder and run `node checkpoint.mjs` without installing dependencies.
The tests execute repository-authored fixtures only, never learner submissions.

Course repository selected by the owner: `proffesergio/modern-fullstack-react-projects-building`.
The website remains a separate platform. This local course directory is the working
source; remote access, synchronization, or publication is not implied by this guide.
See [references and rights](references.md). Licensing and human curriculum review
remain required before publishing a release.
