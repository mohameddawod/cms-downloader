# CMS-downloader
A CLI python script that automates downloading  the material of any course hosted on the  cms website. also organizes the content in weeks.

## Installation
Clone the repo and install dependencies with python package manger pip

```bash
git clone https://github.com/aboueleyes/cms-downloader.git
cd cms-downloader/
sudo pip3 install -r requirements.txt
```
For Windows
```bash
pip install -r  requirements.txt
```

## Usage
For *GUI* students run this command first 
```bash
sed -i 's/^# //' src/constants.py 
```
Run in interactive mode
```bash
python3 main.py
```
For help
```bash
python3 main.py -h
```
Download all PDF files for all courses
```bash
./main.py -p
```
Download every single file including videos for all courses
```bash
./main.py -a
```
Run in interactive mode but display only new items
```bash
./main.py -f
```
Display announcements of a cousre in interactive mode
```bash
./main.py -n
```
Display all announcements for all courses
```bash
./main.py -an
```
## Features
1.  Parallel downloading
2.  In interactive mode you can use regular expressions in search <br>
3.  Select more than option by Pressing \<tab\>

## Contribution
For any feedback or issues, feel free to open an issue, make sure to keep it as detailed as possible.

If you would like to contribute, feel free to fork the repo, and open a PR. However, please create an issue first with the feature/bug-fix you would like to implement, since it might be in-work already.

## DISCLAIMER
This script is not official, It is simply a personal script shared  for educational purposes only.
