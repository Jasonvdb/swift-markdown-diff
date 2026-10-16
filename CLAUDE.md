# swift-markdown-diff

A fork of [gonzalezreal/swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui) that adds `MarkdownDiff`, a SwiftUI view that shows the diff between two Markdown strings. The package is `swift-markdown-diff`, but the library product and module are still `MarkdownUI`.

## Tests

- Tests are SnapshotTesting snapshot tests that run only on iOS (they are skipped on Mac Catalyst/iPad), so `swift test` on the macOS host does not exercise them.
- Reference snapshots live in `Tests/MarkdownUITests/__Snapshots__/`.
