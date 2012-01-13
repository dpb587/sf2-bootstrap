Simple nginx/php-fpm server for symfony2.

Setup:
    git clone http://github.com/dpb587/sf2-bootstrap/
    cd sf2-bootstrap/
    ./bin/install
    ./bin/startup
    #iptables -A INPUT -p tcp --dport 8080 -j ACCEPT

Link:
    http://localhost:8080/
