## Process this file with automake to produce Makefile.in

DIST_SUBDIRS = \
	zbxalgo \
	zbxaudit \
	zbxavailability \
	zbxconnector \
	zbxcommon \
	zbxcomms \
	zbxcommshigh \
	zbxcompress \
	zbxconf \
	zbxcrypto \
	zbxdb \
	zbxcacheconfig \
	zbxcachehistory \
	zbxcachevalue \
	zbxdbhigh \
	zbxdbwrap \
	zbxdbsyncer \
	zbxdbschema \
	zbxdbupgrade \
	zbxdiag \
	zbxdiscovery \
	zbxembed \
	zbxeval \
	zbxevent \
	zbxexec \
	zbxexport \
	zbxexpr \
	zbxfile \
	zbxgetopt \
	zbxhash \
	zbxhistory \
	zbxhttp \
	zbxicmpping \
	zbxip \
	zbxipcservice \
	zbxjson \
	zbxkvs \
	zbxlog \
	zbxmedia \
	zbxmodules \
	zbxmutexs \
	zbxnix \
	zbxnum \
	zbxodbc \
	zbxparam \
	zbxpreproc \
	zbxprometheus \
	zbxregexp \
	zbxrtc \
	zbxself \
	zbxserialize \
	zbxserver \
	zbxservice \
	zbxshmem \
	zbxsysinfo \
	zbxstats \
	zbxstr \
	zbxtagfilter \
	zbxtasks \
	zbxthreads \
	zbxtime \
	zbxtimekeeper \
	zbxtrends \
	zbxvariant \
	zbxvault \
	zbxversion \
	zbxprof \
	zbxxml

if SERVER
SERVER_SUBDIRS = \
	zbxaudit \
	zbxavailability \
	zbxconnector \
	zbxcompress \
	zbxdb \
	zbxcacheconfig \
	zbxcachehistory \
	zbxcachevalue \
	zbxdbhigh \
	zbxdbwrap \
	zbxdbsyncer \
	zbxdbschema \
	zbxdbupgrade \
	zbxdiag \
	zbxembed \
	zbxeval \
	zbxevent \
	zbxexport \
	zbxexpr \
	zbxhistory \
	zbxhttp \
	zbxicmpping \
	zbxip \
	zbxkvs \
	zbxmedia \
	zbxnum \
	zbxodbc \
	zbxparam \
	zbxpreproc \
	zbxprometheus \
	zbxrtc \
	zbxself \
	zbxserialize \
	zbxserver \
	zbxservice \
	zbxshmem \
	zbxstats \
	zbxstr \
	zbxtagfilter \
	zbxtasks \
	zbxtime \
	zbxtimekeeper \
	zbxtrends \
	zbxvariant \
	zbxvault \
	zbxversion \
	zbxxml
else
if PROXY
PROXY_SUBDIRS = \
	zbxaudit \
	zbxavailability \
	zbxconnector \
	zbxcompress \
	zbxdb \
	zbxcacheconfig \
	zbxcachehistory \
	zbxcachevalue \
	zbxdbhigh \
	zbxdbwrap \
	zbxdbsyncer \
	zbxdbschema \
	zbxdbupgrade \
	zbxdiag \
	zbxembed \
	zbxeval \
	zbxevent \
	zbxexport \
	zbxhistory \
	zbxhttp \
	zbxicmpping \
	zbxip \
	zbxkvs \
	zbxnum \
	zbxodbc \
	zbxparam \
	zbxpreproc \
	zbxprometheus \
	zbxrtc \
	zbxself \
	zbxserialize \
	zbxserver \
	zbxshmem \
	zbxstats \
	zbxstr \
	zbxtagfilter \
	zbxtasks \
	zbxtime \
	zbxtimekeeper \
	zbxtrends \
	zbxvariant \
	zbxvault \
	zbxversion \
	zbxxml
endif
endif

SUBDIRS = \
	zbxalgo \
	zbxcommon \
	zbxcomms \
	zbxcommshigh \
	zbxcompress \
	zbxconf \
	zbxcrypto \
	zbxdbschema \
	zbxdiscovery \
	zbxexec \
	zbxexpr \
	zbxfile \
	zbxgetopt \
	zbxhash \
	zbxhttp \
	zbxip \
	zbxipcservice \
	zbxjson \
	zbxlog \
	zbxmodules \
	zbxmutexs \
	zbxprof \
	zbxnix \
	zbxnum \
	zbxodbc \
	zbxparam \
	zbxregexp \
	zbxsysinfo \
	zbxstr \
	zbxthreads \
	zbxtime \
	zbxvariant \
	zbxversion \
	zbxxml \
	$(PROXY_SUBDIRS) \
	$(SERVER_SUBDIRS) \
	$(AGENT_SUBDIRS)

EXTRA_DIST = \
	zbxwin32 \
	zbxwinservice

## hashicorp and cyberark used to be a separate libraries, remove them at some point in the future
clean: clean-recursive
	rm -rf hashicorp && \
	rm -rf cyberark
.PHONY: clean
