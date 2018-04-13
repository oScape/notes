# Configuration


## Change / Update

- Change domain name or URLs
> Do a sql dump and save the project folders before doing this manipulation.

  - Log in wp-admin and go to Settings > General, then change the URLs and save, expect a 404.
  - Use the [Velvet Blues Update URLs](https://fr.wordpress.org/plugins/velvet-blues-update-urls/) plugins for all link and reference.
  - Check all the URLs in your custom code if you have use absolute path, use ```get_site_url()``` instead.
