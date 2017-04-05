FROM            hwdm/apbase:35e
MAINTAINER      Howard Mei      <howardleomei@gmail.com>

ADD				https://github.com/HowardMei/runitshover/archive/runitshover.tar.gz  /tmp/runitshover.tar.gz

RUN 			apk-install curl runit && sleep 1 && tar zxvf /tmp/runitshover.tar.gz --strip-components=1 -C / && \
				apk-cleanup

ENTRYPOINT      ["/entrypoint"]
