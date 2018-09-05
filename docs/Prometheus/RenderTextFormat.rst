----------------------------
Prometheus\\RenderTextFormat
----------------------------

.. php:namespace: Prometheus

.. php:class:: RenderTextFormat

    .. php:method:: render($metrics)

        :type $metrics: MetricFamilySamples[]
        :param $metrics:
        :returns: string

    .. php:method:: renderSample(MetricFamilySamples $metric, Sample $sample)

        :type $metric: MetricFamilySamples
        :param $metric:
        :type $sample: Sample
        :param $sample:

    .. php:method:: escapeLabelValue($v)

        :param $v:
