@@ -27,14 +27,15 @@ assignees: ''
<!--If applicable, add screenshots to help explain your problem.-->

**Device and Application Information (please complete the following information):**
 - OS Build Number:
 - OS Build:
 - Architecture:
 - Application Version Number:
 - Application Version:

 <!--Run the following commands in Powershell and copy/paste the output.
 - OS Build: "$([Environment]::OSVersion.Version)"
 - Architecture: "$((Get-AppxPackage -Name Microsoft.WindowsCalculator).Architecture)"
 - Application Version: "$((Get-AppxPackage -Name Microsoft.WindowsCalculator).Version)"-->
<!--Run the following commands in Powershell and copy/paste the output.
" - OS Build: $([Environment]::OSVersion.Version)"
" - Architecture: $((Get-AppxPackage -Name Microsoft.WindowsCalculator).Architecture)"
" - Application Version: $((Get-AppxPackage -Name Microsoft.WindowsCalculator).Version)"
-->

**Additional context**
<!--Add any other context about the problem here.-->
