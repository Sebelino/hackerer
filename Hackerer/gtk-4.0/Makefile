original-gresources:
	extract-gresource.sh -i original.gtk.gresource -o original-gresources.tmp
	mv original-gresources.tmp/org/numixproject/gtk/ original-gresources
	rm -r original-gresources.tmp

gtk.gresource: gresources
	glib-compile-resources ./gtk.gresource.xml --sourcedir=./gresources --target gtk.gresource
