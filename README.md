# gh-furik

GitHub CLI extension to show your activities for Retrospective.

```
$ gh furik

### kenchan/gh-furik

- [Issues](https://github.com/kenchan/gh-furik/issues/1): 1.0 Release

### pepabo/colormeshop-wp-plugin

- [IssueComment](https://github.com/pepabo/colormeshop-wp-plugin/pull/154#issuecomment-1100030256): Bump phpcompatibility/phpcompatibility-wp from 2.1.2 to 2.1.3
- [IssueComment](https://github.com/pepabo/colormeshop-wp-plugin/pull/154#issuecomment-1100030509): Bump phpcompatibility/phpcompatibility-wp from 2.1.2 to 2.1.3
- [PullRequestReview](https://github.com/pepabo/colormeshop-wp-plugin/pull/152#pullrequestreview-830114010): Bump squizlabs/php_codesniffer from 3.6.0 to 3.6.1
```

## Installation

```
gh extension install kenchan/gh-furik
```

## Usage

Show your yesterday's activities.

```
gh furik
```

If you use GitHub Enterprise Server, use `--hostname` option.

```
gh furik --hostname your.ghes.hostname
```


The date range can be changed with `--from` and `--to`.

```
gh furik --from 2022-04-01 --to 2022-04-10
```

This extension uses the [GitHub Events API](https://docs.github.com/ja/rest/reference/activity#events). There is a limit to the amount of data that can be get with that API.

## Related Project

- [pepabo/furik: GitHub activity summary for Retrospective](https://github.com/pepabo/furik)

## License

MIT
