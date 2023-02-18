
so recently ig started sending html response insted of json to "unknown" requests. 

i REALLY wanted this to work without login since i don't use ig anymore, tried few ways i knew to get it working without login but it didn't work :/

<p align="center"><img src="https://c.tenor.com/ujlv7g3-a7QAAAAC/pepo-sad-pepe.gif" width="100" height="100" /></p>

anyways since lot of people are using this i will add a temporary login to get this working asap

---

* The Instagram OSINT Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

* The information includes:

* [ profile ] : user id, followers / following, number of uploads, profile img URL, business enum, external URL, joined Recently, etc

* [ tags & mentions ] : most used hashtags and mentioned accounts

* [ email ] : if any email is used anywhere it'll be displayed

* [ posts ] : accessability caption, location, timestamp, caption, picture url, etc
  * ( yet not working correctly with posts instagram marks as 'sensitive cotent' )  

---

## • How To Install

`$ pkg install -y git`

`$ git clone https://github.com/aashishsoni145/osi.ig.git && cd osi.ig`

`$ python3 -m pip install -r requirements.txt`

## • Usage

`$ python3 main.py -u username`

`$ python3 main.py -h`

`-p, --post images info highlight`


## • Update

`$ git pull`
