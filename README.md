These are scripts to act on individual image files. Passed to feh so it will be available as shortcuts while using Feh. Feh is called like this with an alias  in bash.

```
alias f='feh --scale-down \
      	     --keep-zoom-vp \
    	     --draw-exif \
    	     --draw-actions \
	     --auto-rotate \
	     --action1 "~/bin/feh-actions/feh-select %F" \
	     --action2 "~/bin/feh-actions/feh-thumbnail %F" \
	     --action9 "~/bin/feh-actions/feh-delete %F"'
```
