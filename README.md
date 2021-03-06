# Dart Docs Workflow for Alfred

![GitHub release](https://img.shields.io/github/release/techouse/alfred-dart-docs.svg)
![GitHub All Releases](https://img.shields.io/github/downloads/techouse/alfred-dart-docs/total.svg)
![GitHub](https://img.shields.io/github/license/techouse/alfred-dart-docs.svg)


Search the [Dart documentation](https://api.dart.dev/) using [Alfred](https://www.alfredapp.com/).

![demo](demo.gif)

## Installation

1. [Download the latest version](https://github.com/techouse/alfred-dart-docs/releases/latest)
2. Install the workflow by double-clicking the `.alfredworkflow` file
3. You can add the workflow to a category, then click "Import" to finish importing. You'll now see the workflow listed in the left sidebar of your Workflows preferences pane.

## Usage

Just type `dart` followed by your search query.

```
dart stream
```

Either press `⌘Y` to Quick Look the result, or press `<enter>` to open it in your web browser.

### Note

The lightning fast search is powered by [Algolia](https://www.algolia.com) which was generous enough to hand me a big
enough plan to fit the whole [Dart search index](https://api.dart.dev/stable/2.16.2/index.json).
A big thank you to [@algolia](https://github.com/algolia) and [@redox](https://github.com/redox) :heart: :heart: :heart:
