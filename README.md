# WordCount
This project can parse a .cpp file to get its charNum/wordNum/lineNum/codeLineNum/blankLineNum/noteLineNum.

You can use cmd to start it and give it some args.

**Here is the specification**:

-c :to get charNum,output to "result.txt".

-w :to get wordNum,output to "result.txt".

-l :to get lineNum,output to "result.txt".

-a :to get codeLineNum/blankLineNum/noteLineNum,output to "result.txt".

-s :handle all the files that match the patternName under the root directory.

(*-c/-w/-l/-a/-s can have a mutual arg)

-o :output to a certain file.

-e <stopList>:the stopList,won't reckon in the words in it when count the wordNum.

-x :to show a graphical interfaces.

**说明：只有一个可显示字符或无可显示字符的行算空行，“//”或“/*”前只有一个可显示字符的算代码行，不止一个字符算注释行，多行注释除首行都算注释行；
-s查找的根目录为BIN目录；用逗号或空格隔开算一个单词，只有逗号或空格则不算单词**
