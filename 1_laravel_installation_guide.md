
## Laravel Installation Guide

### Step 1: Run this command in PowerShell

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; 
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; 
iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows'))
```

### Step 2: Open your work folder and run the following command

```bash
composer global require laravel/installer
```

### Step 3: Create a new Laravel application

```bash
laravel new example-app
```

When prompted, choose the following options:

1. **Use none**
2. **Use PhpUnit**
3. **No**