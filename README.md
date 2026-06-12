# CodexAutoRelay

CodexAutoRelay is a closed-source macOS desktop utility for relay workflows between Codex and a web-based reviewer.

This repository is the public release home for:

- notarized macOS downloads
- - release notes
  - - privacy information
    - - support information
     
      - Source code is not published in this repository.
     
      - ## What the app does
     
      - - Captures screenshots from a selected display region
        - - Uses OCR to read completion markers from the screen
          - - Relays prompts and replies between a reviewer app and a target app
            - - Supports coordinate calibration for input boxes and copy buttons
              - - Stores optional local session archives for troubleshooting
               
                - ## Download
               
                - Download the latest notarized build from the `Releases` page.
               
                - Recommended asset:
               
                - - `CodexAutoRelay-1.0-1.zip`
                 
                  - The app is distributed outside the Mac App Store as a notarized standalone macOS app.
                 
                  - ## Requirements
                 
                  - - macOS
                    - - Screen Recording permission
                      - - Accessibility permission
                        - - The reviewer app and target app must already be running
                         
                          - ## Why permissions are required
                         
                          - `Screen Recording` is used to capture the selected screen region for OCR and relay steps.
                         
                          - `Accessibility` is used to move focus, click configured points, paste text, and send keyboard shortcuts to the apps in your relay workflow.
                         
                          - ## Install
                         
                          - 1. Download the latest notarized ZIP from `Releases`.
                            2. 2. Extract `CodexAutoRelay.app`.
                               3. 3. Move the app to `Applications`.
                                  4. 4. Open the app.
                                     5. 5. Grant `Screen Recording` and `Accessibility` when prompted.
                                        6. 6. Configure the screen region, input points, copy points, and bundle IDs before starting a session.
                                          
                                           7. ## First-run checklist
                                          
                                           8. 1. Open the `Setup` tab and place the input and copy points on the real targets.
                                              2. 2. Leave the default prompts in place unless you need a custom workflow.
                                                 3. 3. Use the `Calibration` tab to verify clicks, screenshots, and OCR.
                                                    4. 4. Start a short session and confirm the mini HUD and logs behave as expected.
                                                      
                                                       5. ## Documents
                                                      
                                                       6. - [Changelog](CHANGELOG.md)
                                                          - - [Privacy](PRIVACY.md)
                                                            - - [Support](SUPPORT.md)
                                                             
                                                              - ## Distribution note
                                                             
                                                              - CodexAutoRelay keeps cross-app automation behavior, so this release is shipped as a Developer ID signed and Apple-notarized standalone app instead of a Mac App Store build.
                                                             
                                                              - All rights reserved.
                                                              - 
