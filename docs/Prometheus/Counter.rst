-------------------
Prometheus\\Counter
-------------------

.. php:namespace: Prometheus

.. php:class:: Counter

    .. php:attr:: storageAdapter

        protected

    .. php:attr:: name

        protected

    .. php:attr:: help

        protected

    .. php:attr:: labels

        protected

    .. php:method:: getType()

        :returns: string

    .. php:method:: inc($labels = array())

        :type $labels: array
        :param $labels: e.g. ['status', 'opcode']

    .. php:method:: incBy($count, $labels = array())

        :type $count: int
        :param $count: e.g. 2
        :type $labels: array
        :param $labels: e.g. ['status', 'opcode']

    .. php:method:: __construct(Adapter $storageAdapter, $namespace, $name, $help, $labels = array())

        :type $storageAdapter: Adapter
        :param $storageAdapter:
        :type $namespace: string
        :param $namespace:
        :type $name: string
        :param $name:
        :type $help: string
        :param $help:
        :type $labels: array
        :param $labels:

    .. php:method:: getName()

    .. php:method:: getLabelNames()

    .. php:method:: getHelp()

    .. php:method:: getKey()

    .. php:method:: assertLabelsAreDefinedCorrectly($labels)

        :param $labels:
