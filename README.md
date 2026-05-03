# quac-sensor
quac_sensor package

## Summary
publishes various sensors connected to the I2C bus

## sensor_publisher
### publishers
- `imu` : `sensors_msgs/msg/Imu`
- `magnetic_field` : `sensors_msgs/msg/MagneticField`
- `thermal_image/compressed` : `sensors_msgs/msg/CompressedImage`

### parameters
```
disable_imu: bool
disable_magnetometer: bool
disable_thermal_cam: bool
```

