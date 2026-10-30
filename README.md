# Embedded GroupEx Pro Schedule

Provides a block (and, through `openy_prgf_embedded_groupexpro_schedule`, a
paragraph) that renders the GroupEx Pro embedded schedule.

## Install

```
composer require ycloudyusa/embedded_groupexpro_schedule
drush en embedded_groupexpro_schedule
```

Set the GroupEx Pro account id (a positive number) at
`/admin/openy/integrations/groupex-pro/groupexpro`.

## Upgrading from drupal/groupexpro

The module keeps its machine name, so switching packages needs only
`composer remove drupal/groupexpro`, `composer require
ycloudyusa/embedded_groupexpro_schedule` and `drush updb`. The site must have
run the `drupal/groupexpro` 2.x updates first.
