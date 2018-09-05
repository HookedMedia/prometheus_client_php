-----------------
Prometheus\\Gauge
-----------------

.. php:namespace: Prometheus

.. php:class:: Gauge

    .. php:attr:: storageAdapter

        protected

    .. php:attr:: name

        protected

    .. php:attr:: help

        protected

    .. php:attr:: labels

        protected

    .. php:method:: set($value, $labels = array())

        :type $value: double
        :param $value: e.g. 123
        :type $labels: array
        :param $labels: e.g. ['status', 'opcode']

    .. php:method:: getType()

        :returns: string

    .. php:method:: inc($labels = array())

        :param $labels:

    .. php:method:: incBy($value, $labels = array())

        :param $value:
        :param $labels:

    .. php:method:: dec($labels = array())

        :param $labels:

    .. php:method:: decBy($value, $labels = array())

        :param $value:
        :param $labels:

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
