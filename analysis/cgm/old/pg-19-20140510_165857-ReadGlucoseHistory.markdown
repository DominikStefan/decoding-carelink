## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=True, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadGlucoseHistory', page=19, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140510_165857-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 36,
           'packets.received': 588L,
           'packets.transmit': 652L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 2017L,
         'packets.transmit': 2017L}}
```
```
PowerControl SERIAL 584923
ERROR:decocare.stick:size (0) is less than 64 and not 15, which may cause an error.
CRITICAL:decocare.stick:FAILED TO DOWNLOAD ANYTHING, after 4  expected:64
ERROR:decocare.stick:ReadRadio ACK is zero bytes!
