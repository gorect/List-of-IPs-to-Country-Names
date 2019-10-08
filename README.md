# List-of-IPs-to-Country-Names

Tested on Arch Linux

Special thanks to Eric Brechemier for his excellent work on creating the geoipfree-ip2country shell scripts.
https://github.com/eric-brechemier/geoipfree-ip2country.git


run chmod 755 on ip2country-name.pl

*excel part* IF(ISEVEN(ROW(A2)),A2,) and IF(ISODD((ROW(A3)),A3,)




git clone https://github.com/eric-brechemier/geoipfree-ip2country.git
cd into geoipfree* dir
cd into setup dir
chmod +x install.sh
./install.sh
*Select "yes" to auto setup
chmod +x update-data.sh
./update-data.sh
cd ..
./ip2country-name.pl *Some IP address*
Now you should get a country name back out!
