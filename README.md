# ADB_final
NYU Advanced database final projuect

To execute the program, please do:

1. Go to ADB_final folder and open "MainEntry.java" file, then change the value of variable 'fileName' to the absolute path of the file "Adb-project/sample.txt" in you workspace. We use more then 20 test cases to test our project in "test_cases.txt". You could chooose any single case each time and copy it into "Adb-project/sample.txt" for testing.But you need to remove all the comment like "//!@@#$%%&&&*&" in lines. Leaving only command lines.

2. Add a set of operations as the input for the program into file "sample.txt", complying with the format as below:
	begin(T1)
	begin(T2)
	R(T2, x2)
	W(T1, x2, 202)
	W(T2 ,x2, 302)
	end(T2)
	end(T1)
	dump()


3. Run MainEntry.main() function and you will see the execution results in the terminal.


