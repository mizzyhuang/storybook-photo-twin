# Storybook Photo Twin

A Codex plugin containing one skill: `fashion-photo-storybook-twin`.

It adds a separate, flat European children's-picture-book wardrobe twin beside the main person in a real fashion, travel, or street-style photo. The photograph remains real; only the added character is illustrated.

## What the skill preserves

- The original person, background, light, crop, and photographic appearance.
- The source person's recognizable hair, eyewear, clothing silhouette, color blocks, footwear, and a small number of distinctive accessories.

## Illustration direction

- Flat, warm, handmade picture-book color blocks.
- Relaxed, varying pencil or ink contours rather than closed, uniform vector outlines.
- Asymmetrical, casually observed poses and 4–8 loose grouped hair locks.
- Minimal interior marks: visual recognition comes from silhouette and color, not fabric texture or dense clothing detail.

## Install locally

Clone this repository, then add its marketplace file in Codex:

```sh
codex plugin marketplace add /absolute/path/to/storybook-photo-twin/.agents/plugins/marketplace.json
```

Install **Storybook Photo Twin** from the Plugins area, or copy `plugins/storybook-photo-twin/skills/fashion-photo-storybook-twin` into a repository's `.agents/skills/` directory for repository-scoped use.

## Use

Attach a photo and write, for example:

```text
Use $fashion-photo-storybook-twin to add a picture-book wardrobe twin beside the subject.
```

Specify the target person when a photo has more than one plausible subject. The skill asks when that choice is ambiguous.

## Privacy and rights

Use photographs you own or are authorized to edit and share. This plugin does not include or redistribute the test photos used during development.

## License

MIT. See [LICENSE](LICENSE).
