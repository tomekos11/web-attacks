Steps to recreate:

1. Navigate to WSL if on Windows
   
3. git clone --recurse-submodules https://github.com/tomekos11/web-attacks.git (INTO WSL)
   
5. Add to rules to hosts:
  - 127.0.0.1 frontend.wa.local
  - 127.0.0.1 haker.local
  - 127.0.0.1 backend.wa.local

4. docker-compose build
5. docker-compose up -d
