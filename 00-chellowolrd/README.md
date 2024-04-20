c11 standard is used to capture hello.c output into output.txt


INSTRUCTIONS TESTED ON LINUX

To achive this, you'll need to use a compiler that support this standard and follow next steps

1. write down into your terminal the following line

   gcc hello.c -o fileNameYouWant.exe -std=11


2. Once you got your executable, you'll need to capture its output

   ./fileNameYouWant > outputResult.txt

Done! :)
