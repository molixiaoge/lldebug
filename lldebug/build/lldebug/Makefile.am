
INCLUDES =	-I../../include \
			-I../../src \
			-I../../extralib/boost_asio_0_3_9 \
			`lua-config --include`

noinst_LIBRARIES = liblldebug.a

liblldebug_a_CPPFLAGS = -DLLDEBUG_CONTEXT \
						-Wall

#liblldebug_a_LDFLAGS = $(LDFLAGS)

liblldebug_a_SOURCES = \
	../../src/configfile.cpp \
	../../src/sysinfo.cpp \
	../../src/luainfo.cpp \
	../../src/md2.cpp \
	../../src/net/command.cpp \
	../../src/net/connection.cpp \
	../../src/net/echostream.cpp \
	../../src/net/netutils.cpp \
	../../src/net/remoteengine.cpp \
	../../src/context/context.cpp \
	../../src/context/execute.cpp \
	../../src/context/lldebug.cpp \
	../../src/context/luaiterate.cpp \
	../../src/context/luautils.cpp

