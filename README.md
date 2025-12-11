## Add user

```
# Create user 'media' with a home directory
sudo adduser media

# Show UID/GID for 'media'
id media
# Example output: uid=1000(media) gid=1000(media) groups=1000(media), ... , 999(docker)

# Appdata (configs)
sudo chown -R media:media /docker/appdata

# Media root (downloads + library)
sudo chown -R media:media /mnt/data
```
