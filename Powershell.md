### La liste des commandes Unix et leur équivalent PowerShell

* **`cp`** : L'équivalent est la cmdlet **`Copy-Item`**.
* **`rm`** : L'équivalent est la cmdlet **`Remove-Item`**.
* **`cd`** : L'équivalent est la cmdlet **`Set-Location`**.
* **`mkdir`** : L'équivalent est la cmdlet **`New-Item`** (utilisée avec le paramètre `-ItemType Directory`).
* **`man`** : L'équivalent est la cmdlet **`Get-Help`**.
* **`history`** : L'équivalent est la cmdlet **`Get-History`**.
* **`alias`** : L'équivalent est la cmdlet **`Get-Alias`**.
* **`cat`** : L'équivalent est la cmdlet **`Get-Content`**.

### Les commandes PowerShell utilisées pour faire les recherches

Pour trouver la cmdlet complète associée à un nom court ou à une commande familière issue d'Unix, j'ai utilisé la recherche d'alias et de commandes intégrée à PowerShell :

* `Get-Alias cp`
* `Get-Alias rm`
* `Get-Alias cd`
* `Get-Command mkdir` *(Note : mkdir étant une fonction PowerShell qui encapsule la création de dossier, `Get-Command` permet d'inspecter sa nature réelle vers `New-Item`)*.
* `Get-Alias man`
* `Get-Alias history`
* `Get-Command alias`
* `Get-Alias cat`
