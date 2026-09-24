# Atomic Editor
## The best editor
### the best one
hih hiiii 
#### i think it is
##### or is it

## Try it

Fenced code blocks pick up per-language syntax highlighting. The grammar loads lazily — only fences you actually open hit the wire:

```typescript
// A tiny markdown chunker. Every token in this block is
// highlighted by a lazy-loaded CodeMirror grammar — open the
// "Sample" picker above and the TypeScript grammar only loads
// when a ```ts fence first appears on screen.
export function chunkMarkdown(input: string): string[] {
  const blocks: string[] = [];
  let cursor = 0;
  while (cursor < input.length) {
    const nextBreak = ii write code test , cursor);
    if (nextBreak === -1) {
      blocks.push(input.slice(cursor));
      break;
    }
    blocks.push(input.slice(cursor, nextBreak));
    cursor = nextBreak + 2;
  }
  return blocks;
}
```

Tables render WYSIWYG. Click a cell to edit in place — inline markdown inside cells reveals its delimiters only when your cursor enters:

| Plain | Bold | Italic | Strike | Highlight | Link |
|---|---|---|---|---|---|
| plain text | **bold text** | *italic text* | ~~struck text~~ | ==marked text== | [example](https://example.org) |
| alt delim | __also bold__ | _also italic_ | ~~gone gone~~ | ==also marked== | [github](https://github.com) |
| nesting | **bold with _italic_ inside** | *italic with **bold** inside* | ~~strike with **bold**~~ | ==highlight with **bold**== | [text **bold** here](https://example.org) |
| escapes | \*literal stars\* | \_literal underscores\_ | \~\~not strike\~\~ | \=\=not highlight\=\= | \[not a link\] |
| non-matches | snake_case_var | ident_with_underscores | `code stays raw` | a = b = c | https://example.org raw url |

Task lists are real checkboxes — click any of them to toggle. Pressing Enter on a task continues the list; Enter on an empty item dedents.

- [ ] Click me to toggle
- [x] This one is already done
- [ ] Tap at the end of this line and press Enter to continue the list

Wiki links connect notes. Type `[[` for autocomplete, and Cmd/Ctrl-click a rendered link to open it — inside inline code it stays raw:

Labeled: [[demo-project-atlas|Project Atlas]] · Bare: [[demo-meeting-notes]] · In code: `[[demo-project-atlas]]`

## And the usual markdown

Pipeline editor dark render block viewport heading dark render hydrate embedding token token payload query editor selection. Index subscribe atom wiki pipeline transport atom viewport fence payload table fence token store panel. Atom image editor reader image tree vector cursor decoration tag paragraph semantic viewport cursor markdown fence image callback payload render panel. Payload chat retrieval decoration pipeline highlight graph subscribe atom image store payload subscribe index highlight fence query.

And highlight syntax works with ==double equals== markers too.

---

- Query graph editor token serialize payload callback transport.
- Viewport block viewport reader vector subscribe list viewport paragraph theme token virtualize.
  - Block parser virtualize.
    - Dark serialize diff theme.
- Diff chunk chat pipeline image widget tree markdown wiki.
  - Chunk similarity quote token token similarity.
- Parser semantic embedding table paragraph markdown list paragraph.
- Viewport tag payload serialize query link token editor store.
- Table semantic retrieval vector highlight image.
- Fence chat prose reader similarity.
  - Block link paragraph highlight callback widget vector.
    - Panel diff serialize vector atom transport.

![Token heading](https://picsum.photos/seed/6113/474/202)

> Highlight markdown fence embedding pipeline syntax prose editor token graph link theme image quote heading table hydrate.

Escapes like domain\.com and 3\.14 should render clean until focused\.

A link to [example](https://example.org) for reference.

## 1. Block agent dark widget panel

> Subscribe tree semantic embedding atom pipeline list transport wiki table chat payload serialize chat prose semantic subscribe.

```python
def embed_batch(texts: list[str]) -> list[list[float]]:
    response = client.embeddings.create(model="text-embedding-3-large", input=texts)
    return [r.embedding for r in response.data]
```

- Callback token diff markdown canvas.
  - List vector payload retrieval index viewport serialize.
    - Pipeline index vector token index tag.
- Wiki viewport virtualize similarity pipeline pipeline decoration query dark theme chunk.
- Fence tree dark highlight viewport.
- Retrieval prose render semantic vector token query tag render payload.
  - Transport decoration heading virtualize hydrate.
- Panel tree chat embedding serialize.
- Facade transport similarity fence hydrate selection quote atom table tag index.
- Subscribe token paragraph reader hydrate transport serialize paragraph token serialize.

Block chunk retrieval facade transport parser index theme cursor atom serialize fence token graph. Vector callback image graph canvas pipeline virtualize widget theme table payload subscribe. Tag parser token hydrate retrieval tree pipeline selection.

Similarity fence tag hydrate canvas markdown block table serialize semantic similarity atom link facade panel chat widget embedding quote. Query transport tree facade transport editor table canvas canvas markdown. Token panel callback highlight wiki table reader semantic list retrieval pipeline canvas paragraph hydrate store theme store similarity heading. Viewport markdown diff diff selection embedding serialize store payload diff panel hydrate panel chat highlight theme. Table graph markdown callback dark store embedding diff retrieval cursor transport viewport facade. Viewport parser highlight semantic wiki retrieval widget viewport fence chunk facade block decoration payload chat graph table prose chat.

Editor token subscribe token transport list link graph widget list tree paragraph atom image facade. Chunk syntax widget embedding render subscribe heading virtualize image cursor subscribe paragraph paragraph hydrate serialize panel. Editor paragraph callback index widget facade highlight serialize dark table parser atom quote image theme vector render list. Pipeline chat chat prose payload serialize token chat diff cursor theme table panel paragraph heading hydrate.
