# PROJECT
  The zziplib provides read access to zipped files in a zip-archive,
  using compression based solely on free algorithms provided by zlib.
  It also provides a functionality to overlay the archive filesystem
  with the filesystem of the operating system environment.

# AUTHOR
  The project was originally written by Tomi Ollila, later largely
  rewritten by Guido Draheim, and extended with contributions in
  the years to follow. Guido Draheim <guidod@gmx.de> holds the full
  copyright to the zziplib sources.

# COPYING
  The zziplib may be used freely under the restrictions of the
  GNU Lesser General Public License version 2 or later. Alternativly
  the Mozilla Public license can be chosen. The sources are under
  a dual license, as long as the MPL hint is not removed, the modified
  files will be again under a dual license for the final recipient.

# LICENSING
  If you can not use a dynalinked library according to LGPL rules,
  then look at docs/copying.htm for a few hints. Generally the LGPL
  has a way for staticlinking as well as the MPL has a way. Anyway,
  special (paid) licenses can be negotiated with the copyright holder.

# HOMEPAGE
  The zziplib project is hosted at SourceForge, the complete
  documentation can be found at http://zziplib.sf.net - the
  SourceForge servers are also used to distribute the sources
  of the zziplib project. Releases are announced via the
  freshmeat services on http://freshmeat.net/projects/zziplib

# INSTALLATION
  The zziplib sources are built with gnu autotools and they should
  be easy to install on unixish systems via the usual sequence of
  `configure && make && make check && make install`. Many distributors
  ship prebuilt packages e.g. in rpm format. Additionally there are
  MSVC project files shipped along for usage with the Microsoft
  VisualC series of compilers. There should be no problem either
  when crosscompiling the zziplib for a third host platform.

# MAINTAINANCE
  The zziplib library is intentionally a lightweight interface to
  zip files. The author take patches but please consider to put
  complex extensions into separate modules rather than implanting them
  right into the core of the library engine. All Patches and Bug Reports
  should be sent to Guido Draheim <guidod@gmx.de>.
