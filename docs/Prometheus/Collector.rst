---------------------
Prometheus\\Collector
---------------------

.. php:namespace: Prometheus

.. php:class:: Collector

    .. php:attr:: storageAdapter

        protected

    .. php:attr:: name

        protected

    .. php:attr:: help

        protected

    .. php:attr:: labels

        protected

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

    .. php:method:: getType()

        :returns: string

    .. php:method:: getName()

    .. php:method:: getLabelNames()

    .. php:method:: getHelp()

    .. php:method:: getKey()

    .. php:method:: assertLabelsAreDefinedCorrectly($labels)

        :param $labels:
