EXE=lan8770_app

all: $(EXE)

lan8770_app: lan8770_app.c
	$(CC) -o lan8770_app $(CFLAGS) lan8770_app.c -lpthread -lmnl

clean:
	$(RM) $(EXE)

install: $(EXE)
	#@install -D -m 755 $(EXE) $(RAMDISK_DIR)/
	cp -r $(EXE) $(DESTDIR)

