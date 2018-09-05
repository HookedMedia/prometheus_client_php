-----------------------------
Prometheus\\Storage\\InMemory
-----------------------------

.. php:namespace: Prometheus\\Storage

.. php:class:: InMemory

    .. php:method:: collect()

        :returns: MetricFamilySamples[]

    .. php:method:: flushMemory()

    .. php:method:: collectHistograms()

    .. php:method:: internalCollect($metrics)

        :param $metrics:

    .. php:method:: updateHistogram($data)

        :param $data:

    .. php:method:: updateGauge($data)

        :param $data:

    .. php:method:: updateCounter($data)

        :param $data:

    .. php:method:: histogramBucketValueKey($data, $bucket)

        :type $data: array
        :param $data:
        :param $bucket:
        :returns: string

    .. php:method:: metaKey($data)

        :type $data: array
        :param $data:
        :returns: string

    .. php:method:: valueKey($data)

        :type $data: array
        :param $data:
        :returns: string

    .. php:method:: metaData($data)

        :type $data: array
        :param $data:
        :returns: array

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
