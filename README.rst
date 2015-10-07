
Buildout
^^^^^^^^
`Installing build dependencies <http://pythonhosted.org/anybox.recipe.odoo/first_steps.html#installing-build-dependencies>`_

Eseguire i seguenti comandi nel path dove si vuole installare con l’utente di sistema che dovrà eseguirlo

``git clone git@github.com:openerp-italia/buildout.git``

``cd buildout``

``wget https://raw.github.com/buildout/buildout/master/bootstrap/bootstrap.py``

``virtualenv sandbox``

``sandbox/bin/pip uninstall setuptools pip``

``sandbox/bin/python bootstrap.py``

Opzioni personali
-----------------
Configurare le proprie impostazioni nel file ``buildout.cfg``

``options.admin_passwd``

``options.db_host``

``options.db_password``

``options.db_user``

Buildout
--------
Per creare l'istanza, eseguire quindi

``bin/buildout``

Avvio istanza
-------------
Eseguire

``bin/start_odoo``

A questo punto è possibile accedere al sistema all’URL

``http://localhost:8069``
