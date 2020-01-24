Android:
- Tap on popup button
- OnDisappearing from Main page runs
- OnAppearing from PopupPage runs
- Send the app to background
- OnDisappearing is not executed, neither the MainPage nor the PopupPage
- Send the app to foreground
- OnAppearing from MainPage is executed.

Expected behavior:
- Tap on popup button
- OnDisappearing from Main page runs
- OnAppearing from PopupPage runs
- Send the app to background
- OnDisappearing from PopupPage is executed
- Send the app to foreground
- OnAppearing from PopupPage is executed.

iOS
- Tap on popup button
- OnAppearing from PopupPage runs
- OnDisappearing from Main page runs
- Send the app to background
- OnDisappearing is not executed, neither the MainPage nor the PopupPage
- Send the app to foreground
- OnAppearing from MainPage is executed.