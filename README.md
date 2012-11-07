ext4test
========

ext4test is a regression teste suit for testing a filesystem.  In ext4test, it
includes a lot of test cases that are used in a product system, such as append
write, preallocation + DIO, etc.  After running these test cases, a result can
be used to compare with the result of previous version in order to understand
whether there is a regression or not.

In result, some metrics need to be highlighted, e.g. latency, IOPS, bandwidth.
In a product system, in fact it merely is used in a full loaded.  So the latency
might be a more important metric.

Regards,
Zheng
<gnehzuil.liu@gmail.com>
