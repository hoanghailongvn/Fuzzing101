Command line used to find this crash:

/home/kali/Documents/tools/AFLplusplus/afl-fuzz -i /home/kali/Documents/Fuzzing101/Exercise2/my_Solutions/exif-samples -o /home/kali/Documents/Fuzzing101/Exercise2/my_Solutions/out -s 123 -- /home/kali/Documents/Fuzzing101/Exercise2/my_Solutions/install-interface-clang/bin/exif @@ /home/kali/Documents/Fuzzing101/Exercise2/my_Solutions/output

If you can't reproduce a bug outside of afl-fuzz, be sure to set the same
memory limit. The limit used for this fuzzing session was 0 B.

Need a tool to minimize test cases before investigating the crashes or sending
them to a vendor? Check out the afl-tmin that comes with the fuzzer!

Found any cool bugs in open-source tools using afl-fuzz? If yes, please post
to https://github.com/AFLplusplus/AFLplusplus/issues/286 once the issues
 are fixed :)

