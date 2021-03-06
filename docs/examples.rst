Examples of aiozmq usage
========================

There is a list of examples from https://aio-libs/aiozmq/examples
Every example is a correct tiny python program.

.. _aiozmq-examples-rpc-rpc:

Remote Procedure Call
---------------------

.. literalinclude:: ../examples/rpc_simple.py


.. _aiozmq-examples-rpc-pipeline:

Pipeline aka Notifier
---------------------

.. literalinclude:: ../examples/rpc_pipeline.py


.. _aiozmq-examples-rpc-pubsub:

Publish-Subscribe
-----------------

.. literalinclude:: ../examples/rpc_pubsub.py


.. _aiozmq-examples-rpc-exception-trasnslator:

Translation RPC exceptions back to client
-----------------------------------------

.. literalinclude:: ../examples/rpc_exception_translator.py


.. _aiozmq-examples-rpc-custom-value-trasnslator:

Translation instances of custom classes via RPC
------------------------------------------------

.. literalinclude:: ../examples/rpc_custom_translator.py


.. _aiozmq-examples-rpc-incorrect-calls:

Validation of RPC methods
--------------------------

.. literalinclude:: ../examples/rpc_incorrect_calls.py


.. _aiozmq-examples-rpc-subhandlers:

RPC lookup in nested namespaces
-------------------------------

.. literalinclude:: ../examples/rpc_with_subhandlers.py


.. _aiozmq-examples-rpc-dict-handler:

Use dict as RPC lookup table
----------------------------

.. literalinclude:: ../examples/rpc_dict_handler.py


.. _aiozmq-examples-rpc-dynamic-handler:

Use dynamic RPC lookup
----------------------

.. literalinclude:: ../examples/rpc_dynamic.py
