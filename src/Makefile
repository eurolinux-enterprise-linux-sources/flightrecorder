VERSION = 0.91

.PHONY: install
install:
	install trace-cmd -D ${DESTDIR}/etc/rc.d/init.d/trace-cmd
	install trace-cmd.config -D ${DESTDIR}/etc/sysconfig/trace-cmd.config
	install trace-cmd.logrotate -D ${DESTDIR}/etc/logrotate.d/trace-cmd
