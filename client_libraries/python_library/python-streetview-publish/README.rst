Python Client for Street View Publish API (`Alpha`_)
==================================================================================================

`Street View Publish API`_: The Street View Publish API allows your application to publish 360 photos to
Google Maps, along with image metadata that specifies the position,
orientation, and connectivity of each photo. With this API, any app can
offer an interface for positioning, connecting, and uploading user-generated
Street View images.

- `Client Library Documentation`_
- `Product Documentation`_

.. _Alpha: https://github.com/GoogleCloudPlatform/google-cloud-python/blob/master/README.rst
.. _Street View Publish API: https://cloud.google.com/streetview_publish
.. _Client Library Documentation: https://googlecloudplatform.github.io/google-cloud-python/stable/streetview_publish-usage
.. _Product Documentation:  https://cloud.google.com/streetview_publish

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. `Select or create a Cloud Platform project.`_
2. `Enable the Street View Publish API.`_
3. `Setup Authentication.`_

.. _Select or create a Cloud Platform project.: https://console.cloud.google.com/project
.. _Enable the Street View Publish API.:  https://cloud.google.com/streetview_publish
.. _Setup Authentication.: https://googlecloudplatform.github.io/google-cloud-python/stable/google-cloud-auth

Installation
~~~~~~~~~~~~

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install gapic-google-maps-streetview_publish-v1


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install gapic-google-maps-streetview_publish-v1

Next Steps
~~~~~~~~~~

-  Read the `Client Library Documentation`_ for Street View Publish API
   API to see other available methods on the client.
-  Read the `Street View Publish API Product documentation`_ to learn
   more about the product and see How-to Guides.
-  View this `repository’s main README`_ to see the full list of Cloud
   APIs that we cover.

.. _Street View Publish API Product documentation:  https://cloud.google.com/streetview_publish
.. _repository’s main README: https://github.com/GoogleCloudPlatform/google-cloud-python/blob/master/README.rst