#
# WARNING: If you modify the files installed here, change the version
# number of the enigma2-fonts package in enigma2.bb.
#
installdir = $(datadir)/fonts

dist_install_DATA = \
	ae_AlMateen.ttf \
	andale.ttf \
	DejaVuSans.ttf \
	lcd.ttf \
	md_khmurabi_10.ttf \
	nmsbd.ttf \
	LiberationSans-Bold.ttf \
	LiberationSans-BoldItalic.ttf \
	LiberationSans-Italic.ttf \
	LiberationSans-Regular.ttf \
	wqy-microhei.ttc \
        analog.ttf \
        Army_Bold_G.ttf \
        army-digital.ttf \
        Army_Regular_L.ttf \
        ForgottenFuturistShadow.ttf \
        goodtime.ttf \
        nmsbd2.ttf \
        tiny.ttf \
        titles.ttf                  

install-data-hook:
	cd $(DESTDIR)$(datadir)/fonts && \
	$(LN_S) wqy-microhei.ttc fallback.font
