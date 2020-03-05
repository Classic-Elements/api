# api
Demo API for Classic Elements

## How to test
Use a copy of the Classic Elementor plugin from the link below 
| Plugin  | URL |
|---------|-----|
| Classic Elementor | https://github.com/ClassicPress-research/classic-elementor |

Edit the file api.php located in the includes folder - I recommed making a copy of the file on your desktop/safe place for reversion purposes.

1: Change line [38](https://github.com/ClassicPress-research/classic-elementor/blob/master/includes/api.php#L38) to https://raw.githubusercontent.com/Classic-Elements/api/public/templates.json

2: Change line [62](https://github.com/ClassicPress-research/classic-elementor/blob/master/includes/api.php#L62) to https://raw.githubusercontent.com/Classic-Elements/api/public/templates/%d.json

3: Activate the plugin (or install and activate if not already done so) and then edit or create a new page choosing to edit with Elementor and confirm the API is working - you may need to "Sync Library" found under the Elementor >> Tools link in your admin dashboard.

#NOTE:
All testing should be performed on a development/staging site and not the production/live site!

## Advice:
This is not the final version and is subject to changes!
