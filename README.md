# Train-Ticket-Booking-System
Command line interface utilized chinese offical train booking website 12306.com API to quickly search for available trains.

## Description ##

Independent Project: Train-Ticket-Booking-System
Author: Zhekai Jin (scott)

## Functionality & Features ##
* train type search allowed 
* Command line table representation
* universal runnabl on user system

## Dependencies ##
* Python 3 
* docopt
* requests
* colorama
* prettytable 
* setuptools 的使用


## Usage ##
```bash
python3 tickets.py [-gdtkz] from to date
```
Usage:
    tickets [-gdtkz] <from> <to> <date>


Options: | Meaning 
--- | --- 
-h,--help  | Help Menu 
-g | **Bullet**
-d | **Normal**
-t  | **express**
-k  | **quick**
-z  | **direct**

Example:

```
    tickets 北京 上海 2018-03-25   
    tickets -dg 成都 南京 2018-03-25
```


## Compilation and Usage ##
* Step 1: Setting up the virtualenv and Install the dependencies
* Step 2: 
```
git clone git@github.com:ZhekaiJin/Train-Ticket-Booking-System.git [target_directory]
python3 setup.py install
command -v tickets
tickets -gdt 上海 北京 2018-03-25
```
## Screenshots ##
![screenshots](https://github.com/ZhekaiJin/Train-Ticket-Booking-System/blob/master/screenshots/screenshot.png "screenshot")

