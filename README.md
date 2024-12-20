These are scripts to act on individual image files. Passed to feh so it will be available as shortcuts while using Feh. Feh is called like this with an alias  in bash.

```
alias f='feh --scale-down \
      	     --keep-zoom-vp \
    	     --draw-exif \
    	     --draw-actions \
	     --auto-rotate \
	     --action1 "~/bin/feh-actions/feh-select %F" \
	     --action2 "~/bin/feh-actions/feh-thumbnail %F" \
	     --action3 "~/bin/feh-actions/feh-open-gimp %F" \
	     --action4 "~/bin/feh-actions/feh-rate4 %F" \
	     --action5 "~/bin/feh-actions/feh-rate5 %F" \
  	     --action8 "~/bin/feh-actions/feh-undo-delete" \		 
	     --action9 "~/bin/feh-actions/feh-delete %F"'
```

Change the location of the trash directory in feh-delete if required. Remember to make all the action files executable.
