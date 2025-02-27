# v0.5.8

Released 2022-08-16

- properly name the load average entities and remove unit of measure (see #96)
- explicitly turn host reverse hostname lookups while collecting dhcpd stats (see #98)

# v0.5.7

Released 2022-08-07

- new services `pfsense.reset_state_table` and `pfsense.kill_states`

# v0.5.6

Released 2022-07-11

- ensure `state` data is reset each interval

# v0.5.5

Released 2022-07-09

- fixes to help concurrency with the xmlrpc api
- more robust handling of devcie tracker entities
- more robust handling of update entities 

# v0.5.4

Released 2022-07-07

- fixes to help concurrency with the xmlrpc api

# v0.5.3

Released 2022-07-06

- attempt to work with hass < `2022.07`

# v0.5.2

Released 2022-07-06

- fix the background refresh process
- attempt to work with hass < `2022.07`

# v0.5.1

Released 2022-07-06

- background the firmware refresh process

# v0.5.0

Released 2022-07-05

- support hass `2022.07+` (require `2022.4+`)
- proper `update` entity with support for triggering a firmware update
- new `set_default_gateway`, `exec_php` and `exec_command` services

# v0.4.0

Released 2021-12-25

- OpenVPN server sensors (connected client count, bytes sent/received)
- firmware upgrades available binary_sensor
- better logic for unavailable devices (vs value of unknown)
