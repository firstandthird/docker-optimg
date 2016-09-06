## Docker Image optimization

### Usage:

`docker run -v $(pwd):/img firstandthird/optimg`

### Variables

`-e QUALITY=80` - Sets the quality of the jpg optimizer

`-e DEBUG=true` - Switches the output from -q (quiet) to -v verbose on both png and jpg commands
