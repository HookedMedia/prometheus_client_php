---------------------
Prometheus\\Histogram
---------------------

.. php:namespace: Prometheus

.. php:class:: Histogram

    .. php:attr:: storageAdapter

        protected

    .. php:attr:: name

        protected

    .. php:attr:: help

        protected

    .. php:attr:: labels

        protected

    .. php:method:: __construct(Adapter $adapter, $namespace, $name, $help, $labels = array(), $buckets = null)

        :type $adapter: Adapter
        :param $adapter:
        :type $namespace: string
        :param $namespace:
        :type $name: string
        :param $name:
        :type $help: string
        :param $help:
        :type $labels: array
        :param $labels:
        :type $buckets: array
        :param $buckets:

    .. php:method:: getDefaultBuckets()

        List of default buckets suitable for typical web application latency
        metrics

        :returns: array

    .. php:method:: observe($value, $labels = array())

        :type $value: double
        :param $value: e.g. 123
        :type $labels: array
        :param $labels: e.g. ['status', 'opcode']

    .. php:method:: getType()

        :returns: string

    .. php:method:: getName()

    .. php:method:: getLabelNames()

    .. php:method:: getHelp()

    .. php:method:: getKey()

    .. php:method:: assertLabelsAreDefinedCorrectly($labels)

        :param $labels:
