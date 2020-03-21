# Docker compose example

Set up both nginx & phpfpm, with a sample page, available on [localhost:8080](http://localhost:8080/)

```bash
# Go to your own folder
# > cd ~/../c/Users/Patolash/Documents/_dev/docker-compose-example

# Start composition
> docker-compose up

# Stop/rm composition
# Ctrl + c

# Use dc down if launched with -d
> docker-compose down
```

Sources :

- *File docker-compose.yml*
- *Folder sources /src*
- *Folder configs /config*
  - Also contains defaults config files for both images, for reference
