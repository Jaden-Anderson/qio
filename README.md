local: enable full CMake build for QIO 3.0.0
- Fix version number to match autotools
- Fix typo: `-Wl.-rpath=` → `-Wl,-rpath=`
- Add QMP dependency injection via CMake target introspection
- Use absolute paths in qio-config script

Committer: WANG Ting-Xiao <wangtx@ihep.ac.cn>

On branch qio-v3.0.0-release
Changes to be committed:
- modified:   <a href=CMakeLists.txt>CMakeLists.txt</a>
- modified:   <a href=bin/qio-config.cmake.in>bin/qio-config.cmake.in</a>

See <a href=build/patch.qio-v3.0.0-release.diff>build/patch.qio-v3.0.0-release.diff</a>
