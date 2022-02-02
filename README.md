# nicapodcast-CMS

This is a Headless CMS based on Wordpress used as a back-end resource for the Nicapodcast client (https://github.com/ameg47/nicapodcast-client)

## How to run locally:

In order to run it locally I recommend using Local WP (https://localwp.com/).
After installing Local WP you should:

1- Download this repo as a ZIP (Code -> Download as Zip). It should include both the wp-content folder and the local.sql file.
2- Import the repo into Local -> Open Local WP and go to Import Site (top left corner menu).
3- Select the downloaded ZIP file.
4- IMPORTANT! A prompt will ask for Local site name and it has to be "nicapodcasts" OR you have to modify the Site Domain "nicapodcasts.local" on the site overview after importing.
Otherwise the endpoints will not match in the client.
5- Start the site.
