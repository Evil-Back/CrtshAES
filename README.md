# ![image](https://user-images.githubusercontent.com/66049511/119264025-04526600-bbd1-11eb-902e-fdc5c4fa4901.png)
# CrtshAES
Script to find subdomains using Certificate 

# Subdomains

Search subdomains of facebook.com # python crtsh.py  -u facebook.com
![image](https://user-images.githubusercontent.com/66049511/119264193-a4a88a80-bbd1-11eb-8324-10955446a86b.png)

# python crtsh.py  -u facebook.com | sort | uniq | httprobe
![image](https://user-images.githubusercontent.com/66049511/119264261-ea655300-bbd1-11eb-8d82-ef8779636361.png)


# Usage
Usage: crtsh.py [-u|--url] target [-i|--input-file] input_file [-o|--output-file] dest_file [-s|--silent]

Options:
  -h, --help            show this help message and exit

  Arguments:
    -u URL, --url=URL   URL target
    -f INPUT_FILE_LIST, --input_file=INPUT_FILE_LIST
                        Input File (accept multiple values)
    -o OUTPUT_FILE, --output-file=OUTPUT_FILE
                        Output File
    -s, --silent        No printing
# [Telegram](https://t.me/A_E_S_security)
