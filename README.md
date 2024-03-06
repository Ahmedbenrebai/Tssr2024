    •	cp (copy)
	•	Unix: cp source_file destination_file
	•	PowerShell: Copy-Item -Path source_file -Destination destination_file
	•	rm (remove)
	•	Unix: rm file
	•	PowerShell: Remove-Item -Path file
	•	cd (change directory)
	•	Unix: cd directory
	•	PowerShell: Set-Location -Path directory
	•	mkdir (make directory)
	•	Unix: mkdir directory
	•	PowerShell: New-Item -ItemType Directory -Path directory
	•	man (manual)
	•	Unix: man command
	•	PowerShell: Get-Help -Name command
	•	history
	•	Unix: history
	•	PowerShell: $history = Get-History
	•	alias
	•	Unix: alias new_command='existing_command'
	•	PowerShell: New-Alias -Name new_command -Value existing_command
	•	cat (concatenate and display)
	•	Unix: cat file
	•	PowerShell: Get-Content -Path file

Commandes PowerShell utilisées pour la recherche

Get-Command -Name cp, rm, cd, mkdir, man, Get-History, New-Alias, Get-Content
