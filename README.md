# fillit_test_files_generator
Create as many random valid fillit tests files as you want. 

Once in the same folder as the .sh, just execute it with bash:
bash  make_test.sh

9 random valid tests will be generated which you can find in tests/
If you want to generate 10,000 tests, just add 3 0s after the 10 after -lt in the first while. 

Improvements to make:
- add more positions for pieces. All current pieces used for test generation are located at the beginning of the file. Would be nice to add some more and change the random number generation interval. Needs some manual work (or clever trick).
- find a way to mute the warning about the mv (which doesn't change concretely change anything).

