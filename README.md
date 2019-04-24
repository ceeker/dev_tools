# dev_tools
Some useful tool for develop

## wrk
./wrk -c200 -t10 -d30s --latency 'http://www.ceeker.com/info/v1' 
Running 30s test @ http://www.ceeker.com/info/v1
  10 threads and 100 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency    31.32ms    7.43ms 258.41ms   97.21%
    Req/Sec   320.18     32.54   382.00     88.33%
  Latency Distribution
     50%   30.34ms
     75%   31.85ms
     90%   33.64ms
     99%   50.66ms
  95865 requests in 30.09s, 580.65MB read
Requests/sec:   3185.74
Transfer/sec:     19.30MB

## dlv  golang remote debug tool
