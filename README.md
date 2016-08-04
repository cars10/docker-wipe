# docker-wipe.sh
This is a script to cleanup your local docker installation - meaning your data, not the actual installation.
It provides functions to delete all images, containers, volumes (use with care!) or all of it.

## Usage
```bash
./docker-wipe.sh {containers|images|volumes|all} {parameter}
Commands:
  containers   - delete all containers
  images       - delete all images
  volumes      - delete all volumes
  all          - delete all containers, images and volumes
Parameter:
  y - pass this to disable confirmation message and automatically destroy
```

## Contributing
* Fork ( https://github.com/cars10/docker-wipe/fork )
* Create your feature branch (`git checkout -b my-new-feature`)
* Commit your changes (`git commit -am 'Add some feature'`)
* Push to the branch (`git push origin my-new-feature`)
* Create a new pull request


## License
MIT
