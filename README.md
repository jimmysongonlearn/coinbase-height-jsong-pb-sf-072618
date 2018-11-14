
# Coinbase Height

### Test Driven Example


```python
from io import BytesIO
from tx import Tx
from helper import little_endian_to_int

class Tx(Tx):

    def coinbase_height(self):
        '''Returns the height of the block this coinbase transaction is in
        Returns None if this transaction is not a coinbase transaction
        '''
        # if this is NOT a coinbase transaction, return None
        # grab the first input
        # grab the first element of the script_sig (.script_sig.elements[0])
        # convert the first element from little endian to int
        pass
```
