Inertial Measurement Unit (IMU)
======================================
:link_to_translation:`zh_CN:[δΈ­ζ]`

The Inertial Measurement Unit (IMU) can be used as a gyroscope sensor, an acceleration sensor, a sensor with multiple functions or etc. It is mainly used to measure the acceleration and angular velocity of an object, and then calculate the motion attitude of the object.

Adapted Products
-----------------------

+------------+--------------------------------+-------+--------------+-------------------------------------------------------------------------------------------------+----------+
| Name       | Function                       | Bus   | Vendor       | Datasheet                                                                                       |HAL       |
+============+================================+=======+==============+=================================================================================================+==========+
| LIS2DH12   | 3-axis acceler                 | I2C   | ST           | `Datasheet <https://www.st.com/resource/en/datasheet/lis2dh12.pdf>`__                           |  β       |
+------------+--------------------------------+-------+--------------+-------------------------------------------------------------------------------------------------+----------+
| MPU6050    | 3-axis acceler + 3-axis gyro   | I2C   | InvenSense   | `Datasheet <https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf>`__   |  β       |
+------------+--------------------------------+-------+--------------+-------------------------------------------------------------------------------------------------+----------+

API Reference
--------------------

The following APIs have implemented hardware abstraction on the IMU. Users can call the code from this layer directly to write a sensor application, or use the sensor interface in :doc:`sensor_hub <sensor_hub>` for easier development.

.. include:: /_build/inc/imu_hal.inc
