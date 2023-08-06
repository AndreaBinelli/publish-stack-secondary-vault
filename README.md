# publish-stack-secondary-vault

The Dendron vault containing the polished notes, a subset of the ones once written in the primary vault.

Part of the publish-stack project alongside:

- [publish-stack-blog](https://github.com/AndreaBinelli/publish-stack-blog)
- [publish-stack-primary-vault](https://github.com/AndreaBinelli/publish-stack-primary-vault)

## Terminology

- Note: a physical markdown file in the vault
- Leaf note: a note at the end of the hierarchy (like 3d.fdm.voron-printers)
- Hierarchy note: a note corresponding to a partial hierarchy (like 3d and 3d.fdm)
- Category note: the first note of the hierarchy (like 3d)
  - is also a hierarchy note
  - cannot be a leaf note (I will never have a blog post without a category)
- Tag note: a note under the tags category. Referenced only from inside the frontmatter of the leaf notes.

## Concepts

- When I move the dendron notes from the primary-vault, I move just the leaf notes and not the hierarchy notes.
- The hierarchy can change here (could be shrinked), and I can add the corresponding hierarchy notes
- The content of hierarchy notes will not appear anywhere so I've decided to let them blank. Are used just for the title/description.
- The same applies also for tag notes, they should remain blank if created for the title/description.
