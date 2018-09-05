-----------------------------
Prometheus\\CollectorRegistry
-----------------------------

.. php:namespace: Prometheus

.. php:class:: CollectorRegistry

    .. php:method:: __construct(Adapter $redisAdapter)

        :type $redisAdapter: Adapter
        :param $redisAdapter:

    .. php:method:: getDefault()

        :returns: CollectorRegistry

    .. php:method:: getMetricFamilySamples()

        :returns: MetricFamilySamples[]

    .. php:method:: registerGauge($namespace, $name, $help, $labels = array())

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. duration_seconds
        :type $help: string
        :param $help: e.g. The duration something took in seconds.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :returns: Gauge

    .. php:method:: getGauge($namespace, $name)

        :type $namespace: string
        :param $namespace:
        :type $name: string
        :param $name:
        :returns: Gauge

    .. php:method:: getOrRegisterGauge($namespace, $name, $help, $labels = array())

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. duration_seconds
        :type $help: string
        :param $help: e.g. The duration something took in seconds.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :returns: Gauge

    .. php:method:: registerCounter($namespace, $name, $help, $labels = array())

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. requests
        :type $help: string
        :param $help: e.g. The number of requests made.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :returns: Counter

    .. php:method:: getCounter($namespace, $name)

        :type $namespace: string
        :param $namespace:
        :type $name: string
        :param $name:
        :returns: Counter

    .. php:method:: getOrRegisterCounter($namespace, $name, $help, $labels = array())

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. requests
        :type $help: string
        :param $help: e.g. The number of requests made.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :returns: Counter

    .. php:method:: registerHistogram($namespace, $name, $help, $labels = array(), $buckets = null)

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. duration_seconds
        :type $help: string
        :param $help: e.g. A histogram of the duration in seconds.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :type $buckets: array
        :param $buckets: e.g. [100, 200, 300]
        :returns: Histogram

    .. php:method:: getHistogram($namespace, $name)

        :type $namespace: string
        :param $namespace:
        :type $name: string
        :param $name:
        :returns: Histogram

    .. php:method:: getOrRegisterHistogram($namespace, $name, $help, $labels = array(), $buckets = null)

        :type $namespace: string
        :param $namespace: e.g. cms
        :type $name: string
        :param $name: e.g. duration_seconds
        :type $help: string
        :param $help: e.g. A histogram of the duration in seconds.
        :type $labels: array
        :param $labels: e.g. ['controller', 'action']
        :type $buckets: array
        :param $buckets: e.g. [100, 200, 300]
        :returns: Histogram

    .. php:method:: metricIdentifier($namespace, $name)

        :param $namespace:
        :param $name:
