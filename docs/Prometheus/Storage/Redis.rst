--------------------------
Prometheus\\Storage\\Redis
--------------------------

.. php:namespace: Prometheus\\Storage

.. php:class:: Redis

    .. php:method:: __construct($options = array())

        :param $options:

    .. php:method:: setDefaultOptions($options)

        :type $options: array
        :param $options:

    .. php:method:: setPrefix($prefix)

        :param $prefix:

    .. php:method:: flushRedis()

    .. php:method:: collect()

        :returns: MetricFamilySamples[]

    .. php:method:: openConnection()

    .. php:method:: updateHistogram($data)

        :param $data:

    .. php:method:: updateGauge($data)

        :param $data:

    .. php:method:: updateCounter($data)

        :param $data:

    .. php:method:: collectHistograms()

    .. php:method:: collectGauges()

    .. php:method:: collectCounters()

    .. php:method:: getRedisCommand($cmd)

        :param $cmd:

    .. php:method:: toMetricKey($data)

        :type $data: array
        :param $data:
        :returns: string
