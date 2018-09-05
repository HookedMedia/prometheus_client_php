Counter
=======

:Qualified name: ``Prometheus\Counter``
:Extends: :class:`Collector`

.. php:class:: Counter

  .. php:method:: __construct (Adapter $storageAdapter, $namespace, $name, $help[, $labels])

    :param Adapter $storageAdapter:
    :param string $namespace:
    :param string $name:
    :param string $help:
    :param array $labels:
      Default: ``array()``

  .. php:method:: getHelp ()


  .. php:method:: getKey ()


  .. php:method:: getLabelNames ()


  .. php:method:: getName ()


  .. php:method:: getType () -> string

    :returns: string -- 

  .. php:method:: inc ([])

    :param array $labels:
      e.g. ['status', 'opcode'].
      Default: ``array()``

  .. php:method:: incBy ($count[, array $labels])

    :param int $count:
      e.g. 2
    :param array $labels:
      e.g. ['status', 'opcode'].
      Default: ``array()``

