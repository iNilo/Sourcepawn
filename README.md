# SourcePawn Completions for SublimeText 3

A Sublime Text 3 plugin that dynamically genenerates completions for SourcePawn.

Based on [sublime-sourcepawn](https://github.com/austinwagner/sublime-sourcepawn).
Includes [watchdog python module](https://https://github.com/gorakhargosh/watchdog)

## Installing

Clone this repository into a subfolder of your Packages directory.

## Configuration

1. Copy an `SPCompletions.sublime-settings.example` file to `SPCompletions.sublime-settings` in the package folder, open it and change `include_directory` setting to your path.
2. Copy an `SourcePawn.sublime-build.example` file to `SourcePawn.sublime-build` in the package folder and edit it to use **Build** feature in SublimeText.

The path must be an absolute path. Relative paths are unsupported.


## Usage

SP Completions is automatically active on .sp and .inc files. The completion list updates whenever you stop typing for 1 second or when you save the file.
