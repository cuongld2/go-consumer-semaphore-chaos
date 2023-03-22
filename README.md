
```txt
checks.........................: 95.07%  ✓ 1139      ✗ 59  
       { scenario:base }............: 100.00% ✓ 601       ✗ 0   
       { scenario:chaos }...........: 90.11%  ✓ 538       ✗ 59  
     data_received..................: 177 kB  2.9 kB/s
     data_sent......................: 113 kB  1.8 kB/s
     dropped_iterations.............: 3       0.048523/s
     http_req_blocked...............: avg=590.47µs min=3.87µs  med=8.14µs  max=65.92ms  p(90)=12.93µs  p(95)=18.62µs 
     http_req_connecting............: avg=579.97µs min=0s      med=0s      max=65.75ms  p(90)=0s       p(95)=0s      
     http_req_duration..............: avg=111.13ms min=52.02ms med=71.79ms max=434.89ms p(90)=168.12ms p(95)=170.03ms
       { expected_response:true }...: avg=108.43ms min=52.02ms med=66.84ms max=434.89ms p(90)=168.07ms p(95)=170.01ms
       { scenario:base }............: avg=60.89ms  min=52.02ms med=60.51ms max=177.34ms p(90)=66.5ms   p(95)=68.35ms 
       { scenario:chaos }...........: avg=161.71ms min=53.42ms med=161.7ms max=434.89ms p(90)=170.02ms p(95)=174.98ms
     http_req_failed................: 4.92%   ✓ 59        ✗ 1139
     http_req_receiving.............: avg=115.29µs min=50.41µs med=109.6µs max=471.71µs p(90)=158.1µs  p(95)=179.06µs
     http_req_sending...............: avg=43.03µs  min=14.41µs med=37.74µs max=464.35µs p(90)=60.19µs  p(95)=76.32µs 
     http_req_tls_handshaking.......: avg=0s       min=0s      med=0s      max=0s       p(90)=0s       p(95)=0s      
     http_req_waiting...............: avg=110.97ms min=51.89ms med=71.63ms max=434.77ms p(90)=167.98ms p(95)=169.9ms 
     http_reqs......................: 1198    19.376939/s
     iteration_duration.............: avg=138.38ms min=52.26ms med=85.04ms max=31.7s    p(90)=168.51ms p(95)=170.47ms
     iterations.....................: 1199    19.393114/s
     vus............................: 0       min=0       max=8 
     vus_max........................: 13      min=11      max=13
     
     
     
     checks.........................: 100.00% ✓ 1198      ✗ 0   
       { scenario:base }............: 100.00% ✓ 601       ✗ 0   
       { scenario:chaos }...........: 100.00% ✓ 597       ✗ 0   
     data_received..................: 176 kB  2.9 kB/s
     data_sent......................: 113 kB  1.8 kB/s
     dropped_iterations.............: 4       0.065134/s
     http_req_blocked...............: avg=682.2µs  min=3.81µs  med=8.19µs   max=66.93ms  p(90)=13.45µs  p(95)=17.5µs  
     http_req_connecting............: avg=671.31µs min=0s      med=0s       max=66.83ms  p(90)=0s       p(95)=0s      
     http_req_duration..............: avg=121.57ms min=59.14ms med=72.31ms  max=502.32ms p(90)=172.82ms p(95)=265.01ms
       { expected_response:true }...: avg=121.57ms min=59.14ms med=72.31ms  max=502.32ms p(90)=172.82ms p(95)=265.01ms
       { scenario:base }............: avg=63.59ms  min=59.14ms med=60.7ms   max=168.06ms p(90)=67.84ms  p(95)=70.18ms 
       { scenario:chaos }...........: avg=179.93ms min=59.68ms med=168.31ms max=502.32ms p(90)=265.06ms p(95)=273.74ms
     http_req_failed................: 0.00%   ✓ 0         ✗ 1198
     http_req_receiving.............: avg=111.89µs min=47.36µs med=102.31µs max=751.42µs p(90)=157.93µs p(95)=182.76µs
     http_req_sending...............: avg=43.93µs  min=14.92µs med=39.67µs  max=296.96µs p(90)=65.21µs  p(95)=79.89µs 
     http_req_tls_handshaking.......: avg=0s       min=0s      med=0s       max=0s       p(90)=0s       p(95)=0s      
     http_req_waiting...............: avg=121.41ms min=59.01ms med=72.14ms  max=502.18ms p(90)=172.67ms p(95)=264.9ms 
     http_reqs......................: 1198    19.507574/s
     iteration_duration.............: avg=148.53ms min=59.35ms med=99.74ms  max=31.26s   p(90)=173.36ms p(95)=265.56ms
     iterations.....................: 1199    19.523857/s
     vus............................: 1       min=1       max=9 
     vus_max........................: 14      min=11      max=14    
```