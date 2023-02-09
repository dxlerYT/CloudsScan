# 🧨  CloudsScan v1.0

Script to scan subdomains of a domain

## 💻 Supported operating systems:

* ✅ Windows (8, 8.1, 10 and 11)
* ✅ Linux
* ✅ Termux

# 🔧 Installation 

```bash
# Clone the repository
$ git clone https://github.com/dxlerYT/CloudsScan/

# Go into the CS folder
$ cd CS

# Install the requirements
$ python3 -m pip install -r requirements.txt

```
# 🕹 Usage

```bash
$ python3 CS.py -h
usage: CS.py [-h] -d DOMAIN -l FILE [-s] [-sv LOGS_FILE]

Script to scan subdomains of a domain

options:
  -h, --help     show this help message and exit
  -d DOMAIN      Domain
  -l FILE        List of subdomains
  -s             Skip subdomains with the same ip
  -sv LOGS_FILE  Save the results to a file
  
```
Scan a domain using the subdomains list in the "default.txt" file
```
python3 CS.py -d facebook.com -l default.txt
```
Scan a domain using the subdomains list in the file "default.txt" and skip the subdomains with the same ips
```
python3 CS.py -d facebook.com -l default.txt -s
```
Scan a domain using the list of subdomains in the file "default.txt" and save the results in the file "logs.txt"
```
python3 CS.py -d facebook.com -l default.txt -sv logs.txt
```

## license



Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

 
