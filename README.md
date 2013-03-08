Drop .chef/plugins/knife/source_ingredient_emacs.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient emacs
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest available versions of emacs for osx and windows will be downloaded into
your file_cache_path and your data bag path will get an emacs directory
created which will be populated with data bag items for each recent version
of emacs that is available.

