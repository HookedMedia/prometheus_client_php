----------------------------
Prometheus\\Storage\\Adapter
----------------------------

.. php:namespace: Prometheus\\Storage

.. php:interface:: Adapter

    .. php:method:: collect()

        :returns: MetricFamilySamples[]

    .. php:method:: updateHistogram($data)

        :param $data:

    .. php:method:: updateGauge($data)

        :param $data:

    .. php:method:: updateCounter($data)

        :param $data:
