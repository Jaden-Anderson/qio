local: enable full CMake build for QIO 3.0.0
- Fix version number to match autotools
- Fix typo: `-Wl.-rpath=` -> `-Wl,-rpath=`
- Add QMP dependency injection via CMake target introspection
- Use absolute paths in qio-config script

Committer: WANG Ting-Xiao (Advisor: LIU Zhaofeng) <wangtx@ihep.ac.cn>

On branch qio-v3.0.0-release
Changes to be committed:
	modified:   CMakeLists.txt
	modified:   bin/qio-config.cmake.in

See <build/patch.qio-v3.0.0-release.diff>
