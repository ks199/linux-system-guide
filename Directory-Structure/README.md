# Understanding the Linux Directory Structure

### Explaination of System Directories
| Directory | Description |
|-----------|-------------|
|/usr| Installed software, shared libraries, includes files and read-only program data. Important subdirectories include.|
|/usr/bin| User commands.|
|/usr/sbin| System adminstartor commands.|
|/usr/local| Locally customized software. |

### **Important System Directories**
| Directory | Description |
|-----------|-------------|
|/boot| Files needed in order to start the boot process.|
|/var| Variable data specific to this system that should persist between boots. such as a databases, log files and website content may be found.|
|/etc| Configuration files specific to this system.|

### **Temporary & Volatile Directories**
| Directory | Description |
|-----------|-------------|
|/tmp| A world writable space for temporary files. Files which have not been accessed, changed or modified for 10 days are deleted from this directory.|
|/dev| Contains special device files that are used by the system to access hardware.|
|/run| Runtime data for processess started since the last boot. This include process id files and lock files, among other things. The content of this directory are recreated on reboot.|

### **User & Application-Specific Directories**
| Directory | Description |
|-----------|-------------|
| `/home` | Default location for user home directories. |
| `/opt` | Used for installing optional third-party software. |
| `/srv` | Holds data for services like web servers (rarely used in containers). |
| `/root` | Home directory for the root user. |
