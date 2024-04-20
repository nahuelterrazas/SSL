c11 standard is used to capture hello.c output into output.txt


To achive this, I've used gcc compiler which support this standard and followed next steps


INSTRUCTIONS TESTED ON LINUX


1. Write down into your terminal the following line

   gcc hello.c -o fileNameYouWant.exe -std=11



2. Once you got your executable, you'll need to capture its output

   ./fileNameYouWant > outputResult.txt

Done! :)
