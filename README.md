# Apigee Custom

Apigee Custom is a [Radix](https://www.drupal.org/project/radix) kit based on Apigee Kickstart for easy theme customization.

## Usage Drush

Drush can be used to generate a sub-theme of `apigee_kickstart` for you.

1. First, ensure you have a working **Drush 9** installation. See [Drush documentation](https://docs.drush.org/en/master/install/) for details.

2. Navigate to the site root in your terminal, substituting `my-portal` with your directory, i.e. `cd ~/Sites/my-portal`.

3. Run the Drush command, substituting `subtheme` with what you'd like your sub-theme's machine name to be:

    `drush --include="web/themes/contrib/radix" radix:create "subtheme" --kit=web/profiles/contrib/apigee_devportal_kickstart/themes/custom/apigee_kickstart/src/kits/apigee_custom`

Upon completion of the Drush command, you will have a newly created theme at `web/themes/custom/subtheme`.

## Installation Manual

1. Extract the folder and place it in
   `web/themes/custom/fg_dana_apigee`
2.Go to admin panel of the website.
3. Enable FG DANA APIGEE SUB THEME theme and set`FG DANA APIGEE SUB THEME` theme as default theme.

## Customise Theming

Add your custom CSS styles in `fg_dana_apigee/css/subtheme.style.css` and custom scripts in `fg_dana_apigee/js/subtheme.script.js`.

## Learn More

- Check out the [Drupal 8 Theming Guide](https://www.drupal.org/docs/8/theming) to learn more about how to work with Drupal 8 themes.
- Learn how to [Disable Drupal 8 caching during development](https://www.drupal.org/node/2598914).