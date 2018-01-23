# JDspider
京东登录下单
使用帮助
> python scraper-jd.py -h
usage: scraper-jd.py [-h] [-u USERNAME] [-p PASSWORD] [-g GOOD] [-c COUNT]
                     [-w WAIT] [-f] [-s]

Simulate to login Jing Dong, and buy sepecified good

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Jing Dong login user name
  -p PASSWORD, --password PASSWORD
                        Jing Dong login user password
  -g GOOD, --good GOOD  Jing Dong good ID
  -c COUNT, --count COUNT
                        The count to buy
  -w WAIT, --wait WAIT  Flush time interval, unit MS
  -f, --flush           Continue flash if good out of stock
  -s, --submit          Submit the order to Jing Dong
