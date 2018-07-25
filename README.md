# Usefull Drupal 7 Snippets.

This is a list of useful Drupal snippets and functions that I often reference to enhance or improve my sites.
 
 

-  [Administration menu disapppears in Drupal 7](#administration-menu-disapppears-in-drupal-7)

### Administration menu disapppears in Drupal 7
If Administration Menu in your project disappears until you will clear cache. Just add this line of code at the end of settings.php file and refresh a page.
```php
    $conf['admin_menu_cache_client'] = FALSE;
```
