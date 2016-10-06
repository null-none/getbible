Class for use https://getbible.net/

=======
Install
=======

.. code-block:: bash

    pip install api-bible

=======
Example
=======

.. code-block:: python

    from getbible.scripture import API

    params = {'ver': 'makarij'}

    bible = API(params)

    print bible.result()

    params = {'p': 'James'}

    bible = API(params)

    print bible.result()
