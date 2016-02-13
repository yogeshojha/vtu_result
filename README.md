# vtu_result
A python script that fetches the results from results.vtu.ac.in and exports them in Excel format

## Installation
$ git clone https://github.com/yogeshojha/vtu_result.git

$ cd vtu_result
## Requirements
$ sudo pip install lxml

$ sudo pip install requests

$ sudo pip install openpyxl

$ sudo pip install argparse



## Usage
$ python app.py --college-code 1EP --branch cs --year 14 --usn-from 000 --usn-to 100 --file results_cs
--college-code or -c: college code. eg: 1st

--branch or -b: branch of student either cs, or is. eg: cs

--year or -y: year in two digit. eg: 14

--usn-from or -uf: starting usn number in three digit number. eg: 000

--usn-to or -ut: ending usn number in three digit number. eg: 100

--file or -f: name of the file to be created either relative or abolute path eg: results_cs

## Contributing
Feel free to submit a pull request or an issue!
