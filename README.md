# nextcloud
self hosted drive nextcloud server


when adding external disk there may be problem that nextcloud don't detect it when using docker , folliwing commands will help


```
docker exec -it <nextcloud container id> ls -la /mnt/exteranlD //  will show data in external drive

docker exec -it <nextcloud container id> occ files:scan --all

```
