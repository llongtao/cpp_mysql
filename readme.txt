# install libraries
conda install -c anaconda boost
sudo apt-get install  libmysqlcppconn-dev

# compile
g++ main.cpp -lmysqlcppconn -o out

# run
./out


# References
https://dev.mysql.com/doc/connector-cpp/1.1/en/connector-cpp-getting-started-examples.html
https://stackoverflow.com/questions/45325562/mysql-connector-cpp-in-centos-6-undefined-reference-to
http://download.nust.na/pub6/mysql/tech-resources/articles/mysql-connector-cpp.html
