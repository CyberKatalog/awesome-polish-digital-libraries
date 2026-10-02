# Contributing

Thank you for every new entry. The rules are short.

## Acceptance criteria

- The service is Polish or holds Polish digital collections.
- The service is publicly available online.
- The service is actively maintained.
- The link uses https and leads directly to the service, not to an intermediary.

## Two language versions

The list has an English version in [README.md](README.md) and a Polish one in [README.pl.md](README.pl.md). Add every entry to both files, in the same section and at the same position.

## Entry format

Every entry looks exactly like this:

```
- [Name](https://address) - description.
```

- The name is the original Polish name of the service, in both language versions.
- The description is 1-2 sentences ending with a full stop: in English in README.md, in Polish in README.pl.md.
- The entry goes into the right section.
- Entries within a section are sorted alphabetically by name.
- One service per pull request.

## Style

- Only the plain hyphen `-`, no typographic dashes.
- Only straight quotes `"`.
- No HTML comments.
- No bold or other decoration in descriptions.

## Process

1. Fork the repository.
2. Create a separate branch for your entry.
3. Open a pull request.
4. Write the pull request title and description in English. The title follows Conventional Commits, for example `feat: add Academica`.
5. The link-check CI must pass before the entry is merged.

## Dead links

If you find a dead link, report it as an issue or open a pull request that fixes or removes the entry.
