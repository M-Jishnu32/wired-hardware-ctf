plug the rrequired hardware 
went to terminal
command bluetoothctl
 c: scan on
  device name: Zephyr
  copy mac id
 c: scan off
  connect 'mac id'
 c: menu gatt
  we can see firmware characteristics and battery chaaracteristics
 c: list-attributes
 c: select-attribute 'uuid'
 here put the 1st 4 characters off uuid and we get our required info for the flag
 flag is wired{Zephyr_1.0_100}
