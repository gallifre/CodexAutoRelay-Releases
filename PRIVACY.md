# Privacy

This document describes the intended data handling of the CodexAutoRelay app build distributed from this repository.

## Local behavior

CodexAutoRelay runs locally on your Mac as a desktop automation utility. The app may process screenshots of the selected region, OCR text, rendered prompts, clipboard text that you choose to import, local logs, optional session archive files, and app settings such as coordinates, bundle IDs, and timing values.

## Permissions

The app requests Screen Recording to capture the configured region for OCR and relay steps. The app requests Accessibility to click, focus, paste, and send keyboard shortcuts in your configured workflow.

## Local storage

The current app build stores settings and prompt configuration in local app preferences. If you enable persistent archives, the app may also store screenshots, OCR output, prompts, and logs in Documents/CodexAutoRelayArchive on your Mac.

## Third-party apps

CodexAutoRelay can move text and screenshots into third-party apps that you choose to run in your workflow. Once content is sent into those apps, the handling of that content is governed by those third-party services.

## Repository scope

This GitHub repository is a distribution and documentation repository. It does not provide a hosted account system or cloud dashboard for CodexAutoRelay.

