Custom Field
============

Supported by Redmine starting from version 2.4

Manager
-------

All operations on the CustomField resource are provided by it's manager. To get access to
it you have to call ``redmine.custom_field`` where ``redmine`` is a configured redmine object.
See the :doc:`../configuration` about how to configure redmine object.

Create methods
--------------

Not supported by Redmine

Read methods
------------

get
+++

Not supported by Redmine

all
+++

.. py:method:: all()
   :module: redminelib.managers.ResourceManager
   :noindex:

   Returns all CustomField resources from Redmine.

   :param int limit: (optional). How much resources to return.
   :param int offset: (optional). Starting from what resource to return the other resources.
   :return: :ref:`ResourceSet` object

.. code-block:: python

   >>> fields = redmine.custom_field.all()
   >>> fields
   <redminelib.resultsets.ResourceSet object with CustomField resources>

filter
++++++

Not supported by Redmine

Update methods
--------------

Not supported by Redmine

Delete methods
--------------

Not supported by Redmine

Export
------

Not supported by Redmine
