
## Basics

- boot
  - `vagrant up`
  
- shutdown
  - `vagrant halt`
  
- reload
  - `vagrant reload`

## Snapshot

### easy snapshot (can only one forward or backword only)

- create snapshot
  - `vagrant snapshot push`

- restore snapshot
  - `vagrant snapshot pop`

### snapshot (can restore snapshot target)

- create snapshot
  - `vagrant snapshot save <SNAP_SHOT_NAME>`
   
- restore snapshot target
  - `vagrant snapshot restore <SNAP_SHOT_NAME>`
  
- show snapshot list
  - `vagrant snapshot list`


### alpine vagrant plugin

- https://github.com/maier/vagrant-alpine
- `vagrant plugin install vagrant-alpine`
- `vagrant init maier/alpine-3.1.3-x86_64`

### alpine package list

- https://pkgs.alpinelinux.org/packages

### failed apk update

- https://github.com/gliderlabs/docker-alpine/issues/55
