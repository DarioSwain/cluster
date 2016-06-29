root@dev:/var/www/github/cluster# composer update
You are running composer with xdebug enabled. This has a major impact on runtime performance. See https://getcomposer.org/xdebug
Running composer as root/super user is highly discouraged as packages, plugins and scripts cannot always be trusted
Loading composer repositories with package information
Updating dependencies (including require-dev)
Your requirements could not be resolved to an installable set of packages.

  Problem 1
    - dario_swain/dep 0.3.x-dev requires dario_swain/main ~0.3.0 -> satisfiable by dario_swain/main[0.3.0] but these conflict with your requirements or minimum-stability.
    - dario_swain/dep 0.3.0 requires dario_swain/main ~0.3.0 -> satisfiable by dario_swain/main[0.3.0] but these conflict with your requirements or minimum-stability.
    - dario_swain/dep 0.3.x-dev requires dario_swain/main ~0.3.0 -> satisfiable by dario_swain/main[0.3.0] but these conflict with your requirements or minimum-stability.
    - Installation request for dario_swain/dep ~0.3.0 -> satisfiable by dario_swain/dep[0.3.0, 0.3.x-dev].

root@dev:/var/www/github/cluster#
