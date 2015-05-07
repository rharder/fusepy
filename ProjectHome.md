## Development of fusepy has moved to github: https://github.com/terencehonles/fusepy ##

<br>

<b>fusepy</b> is a Python module that provides a simple interface to <a href='http://fuse.sourceforge.net/'>FUSE</a> and <a href='http://code.google.com/p/macfuse/'>MacFUSE</a>. It's just one file and is implemented using <i>ctypes</i>.<br>
<br>
See some examples of how you can use fusepy:<br>
<ul><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/memory.py'>memory</a> - A simple memory filesystem<br>
</li><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/loopback.py'>loopback</a> - A loopback filesystem<br>
</li><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/context.py'>context</a> - Sample usage of fuse_get_context()<br>
</li><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/sftp.py'>sftp</a> - A simple SFTP filesystem (requires <a href='http://www.lag.net/paramiko/'>paramiko</a>)</li></ul>

To get started <a href='http://fusepy.googlecode.com/svn/trunk/fuse.py'>download</a> fusepy or just browse the <a href='http://code.google.com/p/fusepy/source/browse/trunk/fuse.py'>source</a>.<br>
<br>
fusepy requires FUSE 2.6 (or later), Python 2.5 (or later) and runs on:<br>
<ul><li>Linux (i386, x86_64, PPC)<br>
</li><li>Mac OS X (Intel, PowerPC)<br>
</li><li>FreeBSD (i386, amd64)</li></ul>

Other versions of fusepy:<br>
<ul><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/fuse24.py'>fuse24.py</a> for Python 2.4 (contributed by Péter Szabó)<br>
</li><li><a href='http://code.google.com/p/fusepy/source/browse/trunk/fuse3.py'>fuse3.py</a> for Python 3 (see also <a href='http://code.google.com/p/fusepy/source/browse/trunk/memory3.py'>memory3.py</a> for an example)</li></ul>

<br>

Related projects:<br>
<br>
<ul><li><a href='http://code.google.com/p/python-llfuse/'>llfuse</a> by Nikolaus Rath.<br>
</li><li><a href='http://code.google.com/p/cusepy/'>cusepy</a> by Manuel Naranjo.</li></ul>

Bitbucket <a href='http://bitbucket.org/vlasovskikh/fusepy-mirror'>mirror</a>.