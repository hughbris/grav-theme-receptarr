# v2.5.0
## 12-12-2025

1. [](#improved)
    * **breaking:** footer template processes site copyright as markdown (b4ff562)
    * fix spacing and tab formatting (#5) - YAML and PHP (2d075b9)
    * rename item template, partial, and blueprint; backward compatible (c7c2989)

# v2.4.1
## 10-12-2025

1. [](#improved)
    * simple translation strings for `DEFAULT_MESSAGE` (c3aa899)
    * fix line endings in some files (1723224)

# v2.4.0
## 08-12-2025

1. [](#improved)
    * move to theme color variables (#3; 217fa49)
    * add generic template-* body classes (#4, ad8de1a)
    * README tweaks

# v2.3.0
## 07-10-2025

1. [](#improved)
    * fallback featured image property renamed and moved to theme config (313ac15)
    * README section on featured images and fallback (cf522b1)
    * use custom Twig `link` tag for site favicon (36e8732)
1. [](#new)
    * default page blueprint including featured image (2833aa3); fallback image in theme blueprint (05cb358)
    * primary_classes block in body block's #primary div (5f9ebbf)
    * added `favicon_image` theme setting (324d427) and blueprint (5ea8512)
    * README section on favicon images (fb29b98)
1. [](#bugfix)
    * add missing omitted bootstrap and google font styles (4e23f8c)

# v2.2.0
## 04-10-2025

1. [](#improved)
    * greatly expanded install instructions in README for unlisted guerilla themes (cb66bfb)
1. [](#new)
    * several blocks for extending header template (cb18ef5)
    * move share buttons into own template (62f9835)
1. [](#bugfix)
    * add custom JS to force scroll of menu sidebar to top on pageload (80b9dd7)

# v2.1.0
## 29-09-2025

1. [](#improved)
    * use `home_url` not `base_url_absolute` in templates (15ed8cc)
    * take site values from site.yaml in templates, not translations (15ed8cc)
    * more sensible screen reader text (640b5b9)
    * better variables/expressions in header template (3f28780, 470b07d)
    * support `site.author.name` as copyright fallback in footer (8b0bdaf)
1. [](#new)
    * page_title block in page head (382b1a0)
    * site_rights block in footer (8b0bdaf)

# v2.0.0
## 28-09-2025

1. [](#improved)
    * CHANGELOG date formats! (8031e1f)
    * name reflecting revived development (8031e1f)
    * requires Grav 1.7 min (8031e1f)
1. [](#new)
    * demo pages and site config from official skeleton so it can work out of the box without the skeleton (8031e1f)

# v1.4.0
## 15-01-2021

1. [](#improved)
    * Fixed autoescaping in preparation for Grav 1.7
1. [](#new)
    * Set Dependency of Grav 1.5.10+ which has support for new **Deferred Block** Twig extension
    * Implement assets rendering using **Deferred Block** Twig extension 

# v1.3.0
## 24-01-2017

1. [](#bugfix)
    * Fix issue when editing the Widget page from Admin
    * Add showchildpages.enabled config option [#6](https://github.com/getgrav/grav-theme-receptar/pull/6)

# v1.2.0
## 14-07-2016

1. [](#improved)
    * Added french
    * Remove unneeded streams from Theme YAML
    * Delete unused composer.json
    * Load custom.css if present in the theme's css folder
1. [](#bugfix)
    * Fix setting the page language in the html tag
    * Fix pagination

# v1.1.0
## 20-01-2016

1. [](#new)
    * Basic Multi-Language support
2. [](#bugfix)
    * Minor bugfixes for navigation

# v1.0.0
## 18-01-2016

1. [](#new)
    * ChangeLog started...
