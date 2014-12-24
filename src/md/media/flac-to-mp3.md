I have:
  - lots of `flac` in `~/Music`
  - mp3 mirrors of the flac in `~/Music-mp3`
  - `flac2mp3.sh` on my `PATH`

`pushd ~/Music && find . -type f -name '*flac' -exec flac2mp3.sh 0 {} ../Music-mp3/{} mtime \; && popd`

See: 
  [this blog post](http://blog.tordeu.com/?p=184`)
