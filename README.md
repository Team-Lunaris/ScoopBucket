# LunarisScoop

[![Tests](https://github.com/Team-Lunaris/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Team-Lunaris/ScoopBucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/Team-Lunaris/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Team-Lunaris/ScoopBucket/actions/workflows/excavator.yml)

This is the official Scoop bucket for Team Lunaris. It contains JSON manifests for apps distributed by our team, making them available via [Scoop](https://scoop.sh), the Windows command-line installer.

## How Do I Use This Bucket?

1. **Add the Bucket**

   Open PowerShell and run:

   ```pwsh
   scoop bucket add LunarisScoop https://github.com/Team-Lunaris/ScoopBucket
   ```

2. **Search and Install Apps**

   To search for an app:

   ```pwsh
   scoop search <app-name>
   ```

   To install an app using its manifest, run:

   ```pwsh
   scoop install LunarisScoop/<manifest-name>
   ```

   For example, to install the Hash Verifier GUI app, run:

   ```pwsh
   scoop install LunarisScoop/Hash-Verifier-GUI
   ```
