## Mysql Binlog

### Config path:
`conf/binlog.json`

	{
	  "mysql": {
	    "host": "127.0.0.1",
	    "port": 3306,
	    "username": "root",
	    "password": "",
	    "slave_id": 1009
	  },
	  "gear_man": {
	      "host": "49.213.11.59",
	      "port": 4730
	  },
	  "cache_path": "./.pos"
	}
	
### Run

```
./bin/binlog -c=./conf/binlog.json
```