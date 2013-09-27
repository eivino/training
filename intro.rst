Introduction
============

Who are we?
-----------

* Patrick Gerken, do3cc, patrick@starzel.de
* Philip Bauer, pbauer, bauer@starzel.de
* We work at `starzel.de <http://www.starzel.de>`_


Who are you?
------------

Please tell us about yourselves:

* name, company, country...
* What is your Plone experience?
* What is your web-development experience?
* What are your expectations for this tutorial?
* Do you know the html of the output of this?

.. code-block:: html

    <div class="hiddenStructure"
         tal:repeat="num python:range(1, 10, 5)"
         tal:content="structure num"
         tal:omit-tag="">
      This is some weird sh*t!
    </div>

  The answer is::

    1 6

* Do you know what the following would return?::

    [(i.Title, i.getURL()) for i in context.getFolderContents()]

* What is your favorite editor?


What will we do?
----------------

Some technologies and tools we use during the training:

* git
* github
* virtualbox
* vagrant
* ubuntu linux
* TTW
* buildout
* TAL
* METAL
* zcml
* grok
* python
* dexterity
* viewlets
* jquery


What we will not do?
--------------------

We will not cover the following topics:

* `Archetypes <http://developer.plone.org/content/archetypes/index.html>`_
* `Portlets <http://developer.plone.org/reference_manuals/old/portlets/index.html>`_
* `Generic Setup <http://developer.plone.org/components/genericsetup.html>`_
* `z3c.forms <http://developer.plone.org/reference_manuals/active/schema-driven-forms/index.html>`_
* `Hosting and Caching <http://developer.plone.org/reference_manuals/active/deployment/index.html>`_
* Theming: `Diazo <http://developer.plone.org/reference_manuals/external/plone.app.theming/userguide.html>`_ or `old-school <http://developer.plone.org/reference_manuals/old/plone_3_theming/index.html>`_
* `Testing and Debugging <http://developer.plone.org/testing_and_debugging/index.html>`_
* `Images and image-scales <http://developer.plone.org/images/index.html>`_
* `i18n and locales <http://developer.plone.org/i18n/index.html>`_


The curriculum for the training is this:

.. toctree::
    :maxdepth: 1
    :numbered: 0




What to expect
--------------

You won't be a professional plone-programmer after this training. But you will know some of the more powerfull features of Plone and should be able to construct a website on your own using these tools. You should also be able to find out where to look for instructions to do tasks we did not cover. You will know most of the core-technologies involved in plone-programming.

If you want to become a plone-developer or plone-integrator you should definitvely read `Martins book <http://www.packtpub.com/professional-plone-4-development/book>`_ and re-read it again.

Most importantly you should practice your skills and not stop here but go forward! One recommended way would be to follow the `todo-app <http://tutorialtodoapp.readthedocs.org/en/latest/>`_.

If you want to stay on the ttw-side of things you could read <Practical Plone <http://www.packtpub.com/practical-plone-3-beginners-guide-to-building-powerful-websites/book>`_.


Documentation
--------------

Follow the training at http://starzel.github.io/training/

.. note::

    You can use the presentation to copy & paste the code but you should try to type at least some of it.

Other
---------

* Ask questions when you have them
* One of us is always there to help you if you are stuck
* We'll make some breaks
* Where is Food, Restrooms
* Contact us after the training: team@starzel.de
* Complete training material with prose: maybe soon ...