# NVIDIA
Function , FindFunctionDefn which takes two strings as inputs: a function name and a program string; 
it returns as an output the line number that contains the function definition.
For example, char strFunctionName[] = "func2"; char strSourceCode[] = "int func1(){ return 0; }\\n int func2(){ return 1; }\\n" "int main(int argc, char*argv[]){ return func2(); }\\n"; FindFunctionDefn( strFunctionName, strSourceCode ) should return 2. Submit the link to the document.
