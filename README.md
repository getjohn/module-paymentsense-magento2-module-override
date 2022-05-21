# Magento2 Module to fix Paymentsense Issues

## Installation

Add this repository to your composer.json as a "vcs" repository (see [Loading a package from a VCS repository](https://getcomposer.org/doc/05-repositories.md#loading-a-package-from-a-vcs-repository))

Then,

`composer require getjohn/module-paymentsensepaymentsoverride`

## What this does

 * adds "checkout agreements" to Hosted and Direct payment methods, so that if you have a "agree to the terms" box, payment still works


