# README

## How to Setup

Create a symbolic link to your clone and restart Xcode.

Example:

```bash
cd <somewhere>
git clone https://github.com/exalted/Xcode-CodeSnippets.git
ln -s $(pwd)/Xcode-CodeSnippets ~/Library/Developer/Xcode/UserData/CodeSnippets
```

## Filename convention

`{IDECodeSnippetPlatformFamily}.{IDECodeSnippetLanguage}.{IDECodeSnippetCompletionPrefix}.codesnippet`

IDECodeSnippetPlatformFamily:

- `all`
- `macosx`
- `iphoneos`
- `watchos`

IDECodeSnippetLanguage:

- `Swift`
- `Objective-C`
- ...
