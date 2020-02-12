# elmo_alarm
e-connect integration for home assistant

### Sample configuration:
```yaml
elmo_alarm:
  host: 'https://connect.elmospa.com'
  vendor: '<vendor>'
  username: '<username>'
  password: '<password>'
  scan_interval: 5
  states:
    - name: 'arm_home'
      zones: [1]
    - name: 'arm_away'
      zones: [1, 2, 3, 4]
    - name: 'arm_night'
      zones: [1, 2, 4]
    - name: 'arm_custom_bypass'
      zones: [3]
 ```
