# File Manager

Releases for File Manager: a desktop app for browsing videos and PDFs, finding duplicates, and matching clips.

## Download

The latest build is on [Releases](https://github.com/xmye/filemanager/releases/latest):

- `file_manager-<version>-py312.pyz` — the app. Required Python packages are baked into this file.

## Run

Needs **Python 3.12**.

```bat
py file_manager-<version>-py312.pyz
```

The first launch installs any missing packages into that Python. Later launches start the app directly.

## Updates

On startup the app checks this folder and the latest release, downloads a newer `.pyz` in the background when one is available, and asks you to restart into it. A new build installs anything it added or raised the first time it runs.

Settings, cache, and the database live in `file_manager_data/` next to the `.pyz`.
