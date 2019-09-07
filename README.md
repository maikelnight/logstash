# logstash with shorewall packet filter iptables firewall - To ElasticSearch 
- Grok Filter to use with logstash and parse shorewall log file (IPv4/IPv6)

- Logstash config File to push to elasticsearch server
- Logstash Regex Filter Adds ipv4/ipv6 true field e.g. dual stack /view filtering
- Bind elasticsearch index with kibana for graphs and analysis

- Use Log Format LOGFORMAT="Shorewall:%s:%s:" in shorewall.conf (both shorewall and shorewall6)
