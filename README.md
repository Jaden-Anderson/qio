local: enable full CMake build for QIO 3.0.0
- Fix version number to match autotools
- Fix typo: `-Wl.-rpath=` → `-Wl,-rpath=`
- Add QMP dependency injection via CMake target introspection
- Use absolute paths in qio-config script

Committer: Wang Ting-Xiao <wangtx@ihep.ac.cn>

On branch qio-v3.0.0-release
Changes to be committed:
	modified:   CMakeLists.txt
	modified:   bin/qio-config.cmake.in

See <a href=build/patch.qio-v3.0.0-release.diff>build/patch.qio-v3.0.0-release.diff</a>
