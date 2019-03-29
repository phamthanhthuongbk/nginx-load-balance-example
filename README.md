# nginx-load-balance-example

https://kipalog.com/posts/Su-dung-NGINX-nhu-mot-Load-Balancer


# Run In docker composer

- docker-compose up --build

# Test 
- in server1: http://localhost:3001/
- in server2: http://localhost:3001/
- in server-master (load balance): http://localhost:5001/
