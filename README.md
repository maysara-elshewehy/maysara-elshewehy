- ## 22-08-2000 ~ 02-01-2026
  > nothing.

- ## 01-01-2026 ~ 00-00-0000
  > everything.

<br>

- ## Plan {A} : `CruxJS` `[R.I.P]`

  > _started: 02-01-2026_

  ![cover](https://raw.githubusercontent.com/maysara-elshewehy/maysara-elshewehy/refs/heads/main/plans/profile-cover.png)

  > I've deleted more code than most developers will ever write.
  >
  > Not from incompetence. From standards no human can sustain.
  >
  > OCPD doesn't let you ship imperfect work. It makes you a prisoner of your own mind.

  > _destroyed: 26-01-2026_

- ## Plan {B} : `MineJS`

  > _started: 27-01-2026_

  > Well.. this time, the architecture defeats the curse.
  >
  > **Three scopes. Clear separation. Zero confusion.**
  >
  > @minejs = Runtime. @minecss = Styling. @mineweb = Framework.
  >
  > **This is how you build forever.**

  - ### Philosophy

    - #### [@minejs](https://github.com/minejs-org)
      > Pure logic. No frameworks. No lock-in.
      >
      > Reusable JS primitives. Works anywhere. Forever.

    - #### [@minecss](https://github.com/minecss-org)
      > Tailwind... but better.
      >
      > Tokens. Semantics. Utils. Zero config.

    - #### [@mineweb](https://github.com/mineweb-org)
      > The framework that gets out of your way.
      >
      > No CSS. No HTML. No icons. No bloat.
      >
      > **< 300 KB. Always.**

    - #### [hmm](https://github.com/minejs-org/hmm)
      > `hmm init MyApp -t app`
      >
      > Setup once. Build forever.

    - #### [nezam.dev](https://nezam.dev)
      > Workspace for dreams too big for tools.
      >
      > `User → Workspace → Modules → ∞`

      ---

  - ### Structure

    - #### @minejs (Runtime)
      > Core primitives - reusable everywhere

      | Package         | Purpose              |
      | --------------- | -------------------- |
      | @minejs/signals | Reactive primitives  |
      | @minejs/hooks   | React-like hooks     |
      | @minejs/store   | State management     |
      | @minejs/http    | HTTP client          |
      | @minejs/db      | Database utilities   |
      | @minejs/i18n    | Internationalization |
      | @minejs/logger  | Logging system       |
      | @minejs/browser | Browser utilities    |
      | @minejs/server  | Server runtime       |
      | @minejs/cli     | CLI framework        |
      | @minejs/hmm     | Package manager      |

      ---

    - #### @minecss (Styling)
      > Tailwind killer - but simpler

      | Package           | Purpose         |
      | ----------------- | --------------- |
      | @minecss/tokens   | Design tokens   |
      | @minecss/semantic | Semantic layer  |
      | @minecss/reset    | CSS reset       |
      | @minecss/utils    | Utility classes |

      ---

    - #### @mineweb (Framework)
      > Everything you need. Nothing you don't.

      | Package             | Purpose                                  |
      | ------------------- | ---------------------------------------- |
      | @mineweb/jsx        | JSX runtime + primitives                 |
      | @mineweb/components | UI components (Button, Navbar, Modal...) |
      | @mineweb/icons      | Icon system (tree-shakeable)             |
      | @mineweb/client     | Client-side framework                    |
      | @mineweb/app        | Full-stack framework                     |
      | @mineweb/plugins    | Plugins (SPA, auth...)                   |
      | @mineweb/extensions | Extensions (theme, toast...)             |

      ---

  - ### The Killer Feature

    > **Complete website < 300 KB**

    ```
    JavaScript bundle: ~130 KB
    ├── Framework
    ├── Used components only
    └── Used icons only (tree-shaken!)

    CSS bundle: ~130 KB
    └── All @minecss utilities

    Total: < 300 KB (production-ready!)
    ```

    ---

  - ### Developer Experience

    ```bash
    # Install
    bun i @minejs/hmm

    # Create project
    hmm init MyApp -t app

    # Start coding (NO CSS, NO HTML, NO ICONS!)
    # Everything just works.
    ```

    **Templates:**
    - `lib` - Clean project structure
    - `cli` - CLI application (@minejs/cli ready)
    - `server` - Backend API (@minejs/server ready)
    - `web` - Full web app (@mineweb ready) **⭐**

    ---

  <br>

> updated: 27-01-2026
