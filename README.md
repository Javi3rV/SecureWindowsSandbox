# SecureWindowsSandbox
Secure Windows Sandbox with shared folder


## How to use
In order to use this file, you need to:
  - Enable Windows Sandbox Feature (there are several tutorials and blogs for this, you need 64bit windows10/11 Pro, enterprise or Education)
  - Create this folder structure on your system: C:\SNDBX\SandBox_Files\Mlwr (another option is to modify the hostFolder option in the file) <-- this is the folder you will share to the SandBox

## Is it 100% safe?
Nothing is 100% safe, but it has this features to reduce the attack surface:
  - vGPU disabled
  - Networking disabled
  - AudioInput disabled
  - VideoInput disabled
  - ProtectedClient enabled
  - PrinterRedirection disabled
  - Clipboard between host-sandbox disabled
  - shared folder is read-only from the sandbox, so you can only store files on it from the host

## How to launch it
Just double click on it, it will launch a clean windows and everything done there will be lost when closed.
