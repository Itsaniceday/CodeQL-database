# CodeQL-database
Creating codeql database with cpp to generate the log files .

cmd command:
D:\codeql-home>.\codeql\codeql.cmd database create -l=cpp -s=D:\codeql-home\drivers\kmdf -c "msbuild /t:rebuild "D:\codeql-home\drivers\kmdf\kmdfecho.sln" /p:UseSharedCompilation=false /p:Configuration=Release /p:Platform=x64 /p:SignMode=off" "D:\codeql-home\databases\kmdf" -j 0
