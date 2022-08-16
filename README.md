# Purpose

Create a UWP application with navigation implemented

# Notable features

- Replace default startup page from `MainPage` to generic `Page1`.  
   This is done in `App.xaml.cs`
- Add navigation from `Page1` to `Page2` and vice-versa via `HyperlinkButton` elements
- Transmit state information from `Page1` -> `Page2` via `OnNavigatedTo` function
- Save Page state using the page cache

# References

- https://docs.microsoft.com/en-us/windows/apps/design/basics/navigate-between-two-pages
