## Getting Started

1. Add <b>.env</b> file to root folder:

   ```bash
   POSTGRES_DB=app
   POSTGRES_USER=postgres
   POSTGRES_PASSWORD=secretpw
   ```

2. Add your <b>video-watchtime-next</b> and <b>video-watchtime-nest</b> repo URLs to <b>.gitmodules</b> file.
3. Run:
   ```bash
   $ git submodule update --init
   $ docker-compose -f docker-compose.yml up
   ```
