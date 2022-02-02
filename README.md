# Nicapodcast-CMS

This is a Headless CMS based on Wordpress used as a back-end resource for the Nicapodcast client (https://github.com/ameg47/nicapodcast-client)

## How to run locally:

In order to run it locally I recommend using Local WP (https://localwp.com/).
After installing Local WP you should:

1- Download this repo as a ZIP (Code -> Download as Zip). It should include both the wp-content folder and the local.sql file.

2- Import the repo into Local: Open Local WP and go to Import Site (top left corner menu).

3- Select the downloaded ZIP file.

4- Put local name to the site.

5- IMPORTANT! You have to modify the Site Domain to "nicapodcasts.local" on the site overview after importing. Otherwise the endpoints will not match in the client.

6- Start the site.

In case there is an error within Local and asks you to switch domain to localhost, you´ll then have to change also the endpoints in the client.
