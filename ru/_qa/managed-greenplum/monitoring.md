# Мониторинг и логи в {{ mgp-name }}

#### За какими метриками и процессами можно следить с помощью мониторинга? {#monitoring}

Для всех типов СУБД можно отслеживать:

* загрузку процессора, памяти, сети, дисков в абсолютных величинах;
* загрузку памяти, сети, дисков в процентах от установленных лимитов для класса хостов соответствующего кластера;
* объем данных кластера БД и остаток свободного места в хранилище данных.

Для всех хостов БД можно отслеживать метрики, специфические для типа соответствующей СУБД. Например, для {{ GP }} можно отслеживать:

* среднее время выполнения запроса;
* количество запросов в секунду;
* количество ошибок в журналах и т. д.

Мониторинг можно осуществлять с минимальным шагом в 5 секунд.

Подробнее о мониторинге см. в разделе [{#T}](../../managed-greenplum/operations/monitoring.md).

{% include [log-duration](../../_includes/mdb/log-duration-qa.md) %}
