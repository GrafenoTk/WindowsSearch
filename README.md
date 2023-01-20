☛ 1. CTRL+SHIFT+ESC, CLIQUE EM ARQUIVO E VÁ EM EXECUTAR NOVA TAREFA, ESCREVA POWERSHELL E DE PRIVILEGIOS DE ADM.

ABRINDO O POWERSHELL COLE ESSE COMANDO:

Get-AppXPackage -AllUsers |where-object {$.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopentMode -Register "$($.InstallLocation)\AppXManifest.xml"}

☛  2. WIN+R ☛  C:\Windows\system32\ctfmon.exe
☛  3. WIN+R ☛ Shell:startup
☛  4. WIN+R ☛   C:\Windows\system32 ☛ PROCURE POR ctfmon.exe, COPIE E COLE NO LOCAL QUE FOI ABERTO NO PASSO 3.


RENICIE O SEU PC.
