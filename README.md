# Docker with Cloudflare Tunnel

- One-time:
    - cloudflared tunnel login
    - cloudflared tunnel create mysite
    - cloudflared tunnel route dns mysite app.example.com
- Compose lifecycle:
    - docker compose up -d
    - docker compose logs -f tunnel
    - docker compose logs -f web
    - docker compose down
      
