# Agents Awesome Design

Useful component libraries and interaction references for building AI chat,
generative results, and agent workspaces.

Maintained alongside [Agents Kit](https://github.com/agents-ui/agents-kit), a
copy-source React library for agent interfaces. This list helps you find the
original projects; the working compositions live in the kit.

[Component catalog](https://agents-ui.github.io/agents-kit/components) ·
[Generative playground](https://agents-ui.github.io/agents-kit/generative) ·
[Workspace example](https://agents-ui.github.io/agents-kit/workspace) ·
[Installation](https://agents-ui.github.io/agents-kit/docs/installation)

## Start with the interaction

- **Build a conversation:** [Prompt Kit](https://prompt-kit.com/) and
  [AI Elements](https://elements.ai-sdk.dev/) cover messages, composers,
  streaming responses, reasoning displays, and citations.
- **Show useful agent work:** [Beautiful UI](https://www.beautifului.dev/) and
  [beUI](https://beui.dev/) explore thinking states, tools, approvals, tasks,
  and structured results.
- **Compose the surrounding product:** [BoardUI](https://www.boardui.com/) and
  [Blocks.so](https://blocks.so/) provide controls, tables, navigation, and
  application compositions.
- **Use motion to explain state:** [Libraries.dev](https://libraries.dev/)
  provides thinking orbs, border effects, and shape transitions.
- **See the pieces working together:** the
  [Agents Kit playground](https://agents-ui.github.io/agents-kit/generative)
  connects generated results to editing, comparisons, and user actions.

## Sources and references used by Agents Kit

| Project | Useful for | Source and license |
| --- | --- | --- |
| [Beautiful UI](https://www.beautifului.dev/) | Agent activity, approvals, context cards, chat, and structured content. | [Source](https://github.com/slev12397/beautiful-ui) · [MIT](https://github.com/slev12397/beautiful-ui/blob/main/LICENSE) |
| [beUI](https://beui.dev/) | AI conversation components, tool results, file diffs, citations, and agent interfaces. | [Source](https://github.com/starc007/ui-components) · [MIT](https://github.com/starc007/ui-components/blob/main/LICENSE) |
| [BoardUI](https://www.boardui.com/) | Shared controls, typography, themes, tables, navigation, and application foundations. | [Source](https://github.com/BoardUI/boardui) · [MIT](https://github.com/BoardUI/boardui/blob/main/LICENSE) |
| [Prompt Kit](https://prompt-kit.com/) | Composable prompt inputs, messages, markdown, code blocks, and streaming chat. | [Source](https://github.com/ibelick/prompt-kit) · [MIT](https://github.com/ibelick/prompt-kit/blob/main/LICENCE.md) |
| [AI Elements](https://elements.ai-sdk.dev/) | AI application interactions, including context usage and checkpoints that informed the kit's implementations. | [Source](https://github.com/vercel/ai-elements) · [Apache-2.0](https://github.com/vercel/ai-elements/blob/main/LICENSE) |
| [Blocks.so](https://blocks.so/) | Larger application patterns, including composers, file queues, setup checklists, and task tables. | [Source](https://github.com/ephraimduncan/blocks) · [MIT](https://github.com/ephraimduncan/blocks/blob/main/LICENSE.md) |
| [Libraries.dev](https://libraries.dev/) | Thinking Orbs, Border Beam, and Liquid Gooey for visible activity and transitions. | [Source](https://github.com/Jakubantalik/Libraries.dev) · [MIT](https://github.com/Jakubantalik/Libraries.dev/blob/main/LICENSE) |

beUI and BoardUI are separate projects. Their roles in Agents Kit are different:
beUI supplies AI interaction patterns; BoardUI supplies the shared control and
theme foundation.

For exact adaptations, pinned revisions, and included notices, see
[Agents Kit's third-party notices](https://github.com/agents-ui/agents-kit/blob/main/THIRD_PARTY_NOTICES.md).
This list does not claim that every upstream component is included in the kit.

## More interactions to study

| Reference | What to explore | Availability |
| --- | --- | --- |
| [Moumen Lab](https://lab.moumen.dev/) | Focused interaction experiments: nested menus, staged uploads, scheduling, command inputs, and permission flows. | [Source](https://github.com/moumen-soliman/lab) · [MIT](https://github.com/moumen-soliman/lab/blob/master/LICENSE) |
| [Loader Buttons](https://loader-buttons.experiments.appllama.io/) | Loading-button motion and how a control communicates work in progress. | Visual reference. No public source license verified. |
| [AlignUI](https://alignui.com/) | Application density, typography, controls, and dashboard composition. | [Base-component license](https://www.alignui.com/license). Commercial Figma assets have [separate terms](https://figma.alignui.com/license). |

These are additional references, not an implementation or porting checklist.

## What we look for

- Interactions that help people understand progress, make a decision, or use a result.
- Public examples that are easy to inspect, with a clear original source.
- Components that can be composed into a real conversation or workspace.
- Source licensing stated separately from visual inspiration and commercial assets.

## Suggest a reference

Open an issue or pull request with the original project link, the interaction it
helps with, and a source/license link when available. Prefer a specific useful
example over another large collection of screenshots.

Each project keeps its own license. A visual reference is not permission to
redistribute its source or paid assets. Preserve the original authors' notices
when adapting code.
