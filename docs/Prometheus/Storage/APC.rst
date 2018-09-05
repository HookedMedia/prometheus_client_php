------------------------
Prometheus\\Storage\\APC
------------------------

.. php:namespace: Prometheus\\Storage

.. php:class:: APC

    .. php:method:: collect()

        :returns: MetricFamilySamples[]

    .. php:method:: updateHistogram($data)

        :param $data:

    .. php:method:: updateGauge($data)

        :param $data:

    .. php:method:: updateCounter($data)

        :param $data:

    .. php:method:: flushAPC()

    .. php:method:: metaKey($data)

        :type $data: array
        :param $data:
        :returns: string

    .. php:method:: valueKey($data)

        :type $data: array
        :param $data:
        :returns: string

    .. php:method:: histogramBucketValueKey($data, $bucket)

        :type $data: array
        :param $data:
        :param $bucket:
        :returns: string

    .. php:method:: metaData($data)

        :type $data: array
        :param $data:
        :returns: array

    .. php:method:: collectCounters()

        :returns: array

    .. php:method:: collectGauges()

        :returns: array

    .. php:method:: collectHistograms()

        :returns: array

    .. php:method:: toInteger($val)

        :type $val: mixed
        :param $val:
        :returns: int

    .. php:method:: fromInteger($val)

        :type $val: mixed
        :param $val:
        :returns: int

    .. php:method:: sortSamples($samples)

        :param $samples:

    .. php:method:: encodeLabelValues($values)

        :type $values: array
        :param $values:
        :returns: string

    .. php:method:: decodeLabelValues($values)

        :type $values: string
        :param $values:
        :returns: array
