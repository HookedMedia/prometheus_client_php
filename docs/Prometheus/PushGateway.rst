-----------------------
Prometheus\\PushGateway
-----------------------

.. php:namespace: Prometheus

.. php:class:: PushGateway

    .. php:method:: __construct($address)

        PushGateway constructor.

        :param $address:

    .. php:method:: push(CollectorRegistry $collectorRegistry, $job, $groupingKey = null)

        Pushes all metrics in a Collector, replacing all those with the same job.
        Uses HTTP PUT.

        :type $collectorRegistry: CollectorRegistry
        :param $collectorRegistry:
        :param $job:
        :param $groupingKey:

    .. php:method:: pushAdd(CollectorRegistry $collectorRegistry, $job, $groupingKey = null)

        Pushes all metrics in a Collector, replacing only previously pushed
        metrics of the same name and job.
        Uses HTTP POST.

        :type $collectorRegistry: CollectorRegistry
        :param $collectorRegistry:
        :param $job:
        :param $groupingKey:

    .. php:method:: delete($job, $groupingKey = null)

        Deletes metrics from the Pushgateway.
        Uses HTTP POST.

        :param $job:
        :param $groupingKey:

    .. php:method:: doRequest(CollectorRegistry $collectorRegistry, $job, $groupingKey, $method)

        :type $collectorRegistry: CollectorRegistry
        :param $collectorRegistry:
        :param $job:
        :param $groupingKey:
        :param $method:
