Steps to recreate:

1. Add to rules to hosts:
  - 127.0.0.1 frontend-1.wa.local
  - 127.0.0.1 frontend-2.wa.haker.local
  - 127.0.0.1 backend.wa.local

2. docker-compose build
3. docker-compose up -d
