# Health-Evolved
Packaged version of 2 custom WordPress plugins meant for use on membership site.
[Link to TDEE Calculator standalone.](https://github.com/sitesbyally/TDEE-Calculator)
[Link to Weight Tracker standalone.](https://github.com/sitesbyally/Weight-Tracker)

Note: both plugins rely on styling from the Elementor builder. More on that below.

## healthEvolved-plugins
- This file combines the TDEE Calculator and Weight Tracker for a membership site.
- Use `[tdee_calculator]` and `[weight_tracker]` shortcodes to show the widgets.
- The TDEE calculator saves the calorie and protein targets to the WordPress user profile.
- The weight tracker only works for logged in users. Non-users will see an error message when they attempt to add a weight/date/note.
  - Users enter their weight, date, and notes and it will save back to their WordPress user profile.
  - It will retrieve the user’s tracked data wherever it is displayed - keep this in mind as it may be really long/big if a user has been tracking their weight for a long time.
  - All values are saved/updated each time a new value is saved, so users can update past notes/weights if needed.
*IMPORTANT:* this plugin must be installed on its own. It will cause errors when installed alongside the TDEEcalculator or weight_tracker-plugin files. 

### Styling notes
Both plugins are styled to use Elementor builder styles. They will inherit the global colours and fonts set in the Elementor builder, so make sure to set those up if you haven’t already. [Here is an article](https://elementor.com/help/how-do-i-set-global-fonts-and-colors/) on how to set global colours and fonts.
