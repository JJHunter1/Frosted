# Frosted
This is my fork just to make a few elements more aesthetic.


## Spicetify Theme

This theme is meant to be a transparent theme for use with backgrounds and blurred effects.

#### *Important:*

This theme would have had to overwrite a lot of the colors set by spicetify, so instead I opted to make the theme with the replace_colors config off. If you install this and your spotify is completely black then you didn't read the installation instructions all the way.

### Installation

To install the current version:

* Clone/Download this repo
* Copy the Frosted folder into your spicetify themes folder
* Run `spicetify config replace_colors 0 current_theme Frosted`
* Profit

### Updating

To update:

* Open a terminal in the folder location and then just `git pull`
* If for some reason this fails, just re-install

### Changing background
Change the variable values in the user.css file with the urls as values, then change the `--bg` variable to whatever variable you want your wallpaper to be.
### Bugs & Issues

I know there are a ton of bugs and I am actively working on fixing them. With that being said, please don't spam this repo with issues, as I know they exist. Please only post issues that make the app unusable, that way I can prioritize those.

I just recently modularized my code using stylus which will make it easier to maintain in the long run and make it easier to fix bugs and add features. Expect plenty of updates.
