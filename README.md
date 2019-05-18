# Drupal 8 module for Jenkins Web Scripts by Alex
<https://github.com/AlexanderGW/jwsa>

### Install
Require package on Composer. The package is marked as a Drupal module, so will be automatically moved to the correct location.

```composer require alexandergw/jwsa_build_info_drupal```

Enable module using Drush

```drush en -y jwsa_build_info_drupal```

Alternatively you can enable the module using the Drupal UI at `/admin/modules`

### Usage

Go to `/admin/reports/status` to view the deployed build information.