the file is downloaded 
searched the details of the ford mustang S550 and found CAN id of rpm of car is 200
In terminal used the command grep '200' ghost.log
=>(1724973002.471613) vcan0 200#77697265647B3370
  (1724973004.283982) vcan0 200#737433696E5F6431
  (1724973007.267199) vcan0 200#646E745F3066665F
  (1724973008.868195) vcan0 200#68316D73336C667D
  (1724973010.087921) vcan0 200#6769746875622069
  (1724973010.888359) vcan0 200#7320796F75722066
  (1724973016.074317) vcan0 200#7269656E64
  (1724973021.679542) vcan0 283#228DE20058405878
  (1724973025.081357) vcan0 200#13CB
we get few hexadeci coded lines
converted the the data after the '#' and got 4 parts of the flag
the flag is formed
