# pythonGenieacsImproved
python connector for Genieacs improved
This is improved Genieacs Connector with Python script or API. 

## Usage

### Clone the Repository
```bash
git clone https://github.com/yamangit/pythonGenieacsImproved.git
```
## Import in your project
```bash
from genieacs import Connection
```
## Sample code
```python
from genieacs import Connection

acs = Connection("x.x.x.x")
# Device search using serial number
data = acs.device_get_by_serial_new("device_serial")

```





