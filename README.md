# Sonor

Sonor is a music player for Subsonic and Navidrome servers for desktop and mobile. It is not publicly available yet; this repository holds what is published for it: today, the LGPL source bundles of the libraries its desktop apps include.

## LGPL source bundles

Sonor's desktop builds (macOS, Linux, Windows) include libmpv, FFmpeg and other libraries
licensed under the GNU Lesser General Public License. They are linked dynamically, and you may
replace them with your own builds.

Each release here carries, per desktop platform, a `sonor-libmpv-sources-<target>.tar` with the
exact source code of those libraries, the patches applied, the build scripts and configuration,
the licence texts, and `README-REBUILD.txt`, which explains how to rebuild the libraries and
replace them in an installed copy of Sonor. Check each bundle against its `SHA256SUMS`.

The release tag matches the Sonor version the bundles were built for. To ask for the source in
another form, open an issue in this repository.
