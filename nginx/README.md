```nginx
105     server {
106         listen 3009;
107
108         location /mall {
109             proxy_pass http://127.0.0.1:9073;
110         }
111
112         location /user {
113             proxy_pass http://127.0.0.1:9200;
114         }
115     }
```

