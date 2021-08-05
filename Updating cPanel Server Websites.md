# Updating cPanel Websites
Please read the documentation thoroughly before attempting to update the cPanel server. You are updating a live version of the site, meaning it is already being used by our users. Follow the guide to minimize the downtimes and errors!

## Steps
Refer to the [Git Guide](https://github.com/sumo-media/beginner-docs/blob/main/GitGuide.md) if you have questions regarding Git.

1. Checkout to the repository's `master` branch.
1. Pull from the remote repository to ensure updated master.
1. Zip everything **inside** the project folder, except for files that is used for local development. Such files and folders are:
    * .env
    * Dockerfile
    * docker-compose.yml
    * *.code-workspace
    * *.sh
    * *.bat
    * .git/

    > Note:
    > * The files listed may have variations, include them as well.
    > * Do not zip the project folder itself but rather its contents!

1. Log in to the cPanel server. Ask sir Ben or somebody else for the login credentials

1. Click on the file manager.
1. Find the folder of the website and open it.
1. Compress everything to create a backup. You will need to use this when the new update breaks something.
1. Upload the updated zip file.
1. **After** upload is done, refresh the folder.
    > Note
    > * It is important you do the next steps **after** the updated zip is uploaded, to minimize the site downtime!

1. Click Select All and deselect the file you do not need to delete. Such files and folders are:
    * .htaccess
    * .env
    * Backup zip file you created moments ago
    * Updated zip file you uploaded

1. Verify that you have not selected any important files. Click delete to remove the old files.
1. Extract the updated zip file.
1. Go the website and check for errors.
1. Once you have validated the everything is working correctly, delete the backup zip file and the updated zip file.

### General notes:
* After deleting the old files, extract the updated files immediately to lessen the site downtime.
* Always check the website, specially the changed parts. Some errors might not show on your local dev environment but might break the live site.
* If you have a big folder, for example assets folder containing a gigabyte of source materials for videos, images, etc. You may not include them in the update zip. Just upload them manually on the site to avoid unnecessary bandwidth waste and to make updates faster.
