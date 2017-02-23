After forking:

1. Make suitable changes to `manifest.yml`

 * You will need to modify the `name`, and `host` attributes.
 * You may need to modify the `domain` attribute as well

2. **DEPLOY** (if you've not setup the linkage with BlueMix, you will need to now)

3. **Login** to BlueMix, and **bind** your MySQL or ClearB service instance(s) to this app

4. **Go to** the application URL

5. **Choose** the MySQL service you want to admin and **Login**. You are good to go!

 * if you don't recall the `user-id` and `password` (which is highly likely) you can get it from the application details page on **BlueMix Dashboard**. (look at the details of the `VCAP_SERVICES` variable)