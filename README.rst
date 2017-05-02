Class for use https://getbible.net/

.. image:: https://badge.fury.io/py/api-bible.svg
    :target: https://pypi.python.org/pypi/api-bible

=======
Install
=======

.. code-block:: bash

    pip install api-bible

=======
Example
=======

.. code-block:: python

    from getbible import scripture

    params = {'ver': 'makarij'}

    bible = scripture.API(params)

    print bible.result()

    params = {'p': 'James'}

    bible = scripture.API(params)

    print bible.result()

=======
Donation
=======

.. image:: https://img.shields.io/badge/Donate-PayPal-green.svg
  :target: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YYZQ6ZRZ3EW5C
