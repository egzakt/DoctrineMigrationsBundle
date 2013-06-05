DoctrineMigrationsBundle
========================

This bundle integrates the [Doctrine2 Migrations library](http://www.doctrine-project.org/projects/migrations).
into Symfony so that you can safely and quickly manage database migrations.

Documentation on how to install and use this bundle is available in the
Symfony2 [documentation](http://symfony.com/doc/current/bundles/DoctrineMigrationsBundle/index.html).

## Services Container Injection
This version of DoctrineMigrationBundle provide the service container injection into migration files for Symfony 2.0.

**Changes versus the original version:**

* Services container access into migrations.
* Genarated migration file implement `ContainerAwareInterface` by default.
* `postUp()` function added to the generated migration file as remember and
 for user comfort.