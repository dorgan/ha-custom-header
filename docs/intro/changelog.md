---
title: Change Log
index: 3
---

## Change Log

Major fixes, added features, or breaking changes.

</br>

## Sept. 19th 2020 - v1.7.9

Added Features:

 - fit_tabs: If the number of tabs fits on screen, fill the header's width with them.

Fixes:

- Fixes hiding tabs by title if the title includes spaces
- Corrects background and element color defaults
- Fixes issues related to button/tab presses on mobile devices

## June 10th 2020 - v1.5.8

Added Features:

- tab_text_only: Display only text on tabs, no icons
- header updates on device orientation change

## June 8th 2020 - v1.5.3

Added Features:

- restrict_users: This will prevent non-admin users from disabling CH and accessing CH settings.
- tab_icons_and_text: Will display both icons and text on tabs.
- tab_text: Change a tab's text, works just like button_text and accepts templates.

## June 2nd 2020 - v1.5.0

Fixes:

- Rebuild after exiting raw config editor (page refresh no longer required)

## May 23rd 2020 - v1.4.7

Added Features:

- Allow 'null' for default_tab (useful for exceptions)
- `{{ hassVersion }}` template variable

Fixes:

- HA 0.110+ compatibility
- Styling fixes for one view setups
- Fix active tab styling on dashboard switch

## March 27th 2020 - v1.3.3

Added Features

- hide_reload_resources for yaml mode users
- hide_ch_settings
- Tabs will now fill full width of header by default, to restore the previous way of leaving space for buttons to compact on scroll use button_scroll: true

Fixes:

- HA 0.107+ compatibility
- Things like viewTitle in header/button text should now update on view change.
- Improvements to active tab to make sure it is shown when selected and not cut off.
- Fixed tab redirects still being active in disabled mode

## Jan. 21st 2020 - v1.2.2

Added Features:

- New template variables: deviceID, isAdmin, isOwner, userID, userAgent, viewTitle, viewPath, viewIndex, url
- New exception conditions: is_admin, is_owner, tab, template
- Can use a user's ID instead of name in user condition

Fixes:

- Tabs not hiding while in kiosk mode.
- Respects new theme variables for header text and background.
- Bottom margin in kiosk mode.

## Jan. 8th 2020 - v1.1.8

- Fix button text justification
- Fix for view names containing the letters "to" being detected as a range
- Fix for boolean reporting in test_template:
- Fix for notification dot color
- Fix for cards overlapping in split mode and footer mode

## Dec. 28th 2019 - v1.1.6

- Adds default_tab_on_refresh option
- Adjusts panel view styling
- Fixes animated shadow

## Dec. 24th 2019 - v1.1.4

- Uses default HA header text as default for header_text
- Adds shadow to header can be toggled with `shadow: true` or `shadow: false`
- Adds split mode to split header into a header and footer, flip order with footer_mode.
- Listens for theme changes and updates accordingly

## Dec. 20th 2019 - v1.1.1

- iOS styling fixes
- Don't redirect to default tab on refresh

## Dec. 19th 2019 - v1.1.0

- Panel view display fixes
- Adds `test_template:`

## Dec. 18th 2019 - v1.0.7

Fixes for:

- View sizing
- 12 hour template
- Default tab
- Current tab indicator

## Dec. 17th 2019 - v1.0.6

- Fix "custom header" menu item

## Dec. 17th 2019 - v1.0.5

- Addresses "Tried to serve up '/config/www/community/custom-header/lit-element.js.map' but it does not exist"

## Dec. 17th 2019 - v1.0.4

- View style fixes
- Panel mode style fixes
- Insert custom header option in disabled mode

## Dec. 16th 2019 - v1.0.3

- Fix default_tab's default so it's not 0 when not set
- Make sure voice icon exists even if voice options are set in config
- Resize header only in Lovelace view and only when needed

## Dec. 16th 2019 - v1.0.2

- Adds localization to editor
- Fixes default tab not working in kiosk mode
- Fixes reversed text on buttons
- Adds hide_header to editor

## Dec. 15th 2019 - v1.0.1

- Added `hide_header: true` to hide the header and still allow sidebar to be swiped in from left.
- Fixed background not filling behind header causing transparent headers to show no background underneath.

## Dec. 15th 2019 - v1.0.0

- Initial release
