# hdtest - easy way to check speed of your HDD/SSD/NVMe

How its work:
Clone this:
git clone https://github.com/Akhaladze/hdtest

Install fio package 
sudo apt install fio  

Run script: 
./hddtest.sh  

Example output: 

Results:  

Sequential Q32T1 Read: 487MB/s [   14 IOPS] 
Sequential Q32T1 Write: 405MB/s [   12 IOPS]  

4KB Q8T8 Read: 346MB/s [   86660 IOPS]  
4KB Q8T8 Write: 326MB/s [   81692 IOPS] 

4KB Q32T1 Read: 289MB/s [   72495 IOPS] 
4KB Q32T1 Write: 254MB/s [   63701 IOPS]  

4KB Read: 25MB/s [   6308 IOPS] 
4KB Write: 71MB/s [   17894 IOPS] 
