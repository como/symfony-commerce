Symfony Commerce Edition
========================

Welcome to the Symfony Commerce Edition - a fully-functional Symfony2
distribution based on the standard edition designed for agile e-commerce development. If you want
to learn more about the features included, see the "What's Inside?" section.

This document contains information on how to download and start using Symfony.
For a more detailed explanation, see the
[Installation chapter](http://symfony.com/doc/current/book/installation.html)
of the Symfony Documentation.

1) Download the Commerce Edition
--------------------------------

If you've already downloaded the standard edition, and unpacked it somewhere
within your web root directory, then move on to the "Installation" section.

To download the standard edition, you have two options:

### Download an archive file (*recommended*)

The easiest way to get started is to download an archive of the standard edition
(http://symfony.com/download). Unpack it somewhere under your web server root
directory and you're done. The web root is wherever your web server (e.g. Apache)
looks when you access `http://localhost` in a browser.

### Clone the git Repository

We highly recommend that you download the packaged version of this distribution.
But if you still want to use Git, you are on your own.

Run the following commands:

    git clone http://github.com/symfony/symfony-standard.git
    cd symfony-standard
    rm -rf .git


What's inside?
---------------
The Symfony Standard Edition comes pre-configured with the following bundles:
	
* **ComoPointOfSaleBundle** (Coming Soon)
* **ComoTransactionBundle** (Coming Soon)
* **ComoCatalogueBundle** (Coming Soon)
* **FrameworkBundle** - The core Symfony framework bundle
* **SensioFrameworkExtraBundle** - Adds several enhancements, including template
  and routing annotation capability ([documentation](http://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/index.html))
* **DoctrineBundle** - Adds support for the Doctrine ORM
  ([documentation](http://symfony.com/doc/current/book/doctrine.html))
* **TwigBundle** - Adds support for the Twig templating engine
  ([documentation](http://symfony.com/doc/current/book/templating.html))
* **SecurityBundle** - Adds security by integrating Symfony's security component
  ([documentation](http://symfony.com/doc/current/book/security.html))
* **SwiftmailerBundle** - Adds support for Swiftmailer, a library for sending emails
  ([documentation](http://symfony.com/doc/2.0/cookbook/email.html))
* **MonologBundle** - Adds support for Monolog, a logging library
  ([documentation](http://symfony.com/doc/2.0/cookbook/logging/monolog.html))
* **AsseticBundle** - Adds support for Assetic, an asset processing library
  ([documentation](http://symfony.com/doc/2.0/cookbook/assetic/asset_management.html))
* **JMSSecurityExtraBundle** - Allows security to be added via annotations
  ([documentation](http://symfony.com/doc/current/bundles/JMSSecurityExtraBundle/index.html))
* **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
  the web debug toolbar
* **SensioDistributionBundle** (in dev/test env) - Adds functionality for configuring
  and working with Symfony distributions
* **SensioGeneratorBundle** (in dev/test env) - Adds code generation capabilities
  ([documentation](http://symfony.com/doc/current/bundles/SensioGeneratorBundle/index.html))
* **AcmeDemoBundle** (in dev/test env) - A demo bundle with some example code

Enjoy!
