# pim-sku-finder
Python App to search sku by incomplete search or exact match

pip install requirements.txt

SG Products (main.py) run on port 5000
SG Products (main_id.py) run on port 5001

/input
/reload (with x-api-key)

run under systemctl pim-sku-finder-sg and pim-sku-finder-id

environments:
API_KEY=x-api-key
DB_HOST=localhost
DB_USER=username
DB_PASS=yourpassword
DB_NAME_SG=pim_master
DB_NAME_ID=pim_indo
PORT_SG=5000
PORT_ID=5001
