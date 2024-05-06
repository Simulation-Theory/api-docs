Usage
=====

.. _installation:

API Key
------------

To generate an API key you need a SimTheory account, get one here:

https://simtheory.ai/chat/api-keys

Testing your API key
---------------------------

To make a basic API call to SimTheory you can do this to get your current tokens remaining:

.. code-block:: bash

   curl -X GET "https://simtheory.ai/chat/api/v1/usage" -H "accept: application/json"
