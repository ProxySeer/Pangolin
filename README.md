# Pangolin Security

**Pangolin** is a security application designed to encrypt, decrypt and securely preview your files without permanently decrypting them onto the hard drive.

This project is the modern evolution of an older application called **VTCrypt**, originally developed around 6 years ago, now rebuilt with a simpler architecture, plugin support and advanced Ghost View technology.

---

# What is Pangolin?

Pangolin allows you to encrypt files and folders into the `.encx` format and preview supported encrypted content directly through **Ghost View** technology.

With Ghost View, files can be viewed without being fully extracted or permanently decrypted onto the disk whenever possible.

Supported content includes:

- Videos
- Audio files
- Office documents
- PDFs
- Images
- And many common file formats

---

# Features

- File & folder encryption
- Secure decryption
- `.encx` encrypted file format
- Drag & Drop support
- Session-based Master Password
- Quick Encrypt / Quick Decrypt
- Ghost View secure preview system
- Plugin-based architecture
- Windows shell integration
- Secure standalone EXE packaging
- Preview packed files without extraction

---

# Available Plugins

## Pangolin Media Player Plugin

Allows encrypted media files to be played directly using Ghost View technology without permanently decrypting them.

Supported content:

- Video files
- Audio files
- Common multimedia formats

---

## Pangolin Shell Plugin

Provides Windows right-click context menu integration.

You can directly:

- Encrypt
- Decrypt
- Ghost Preview

files from Windows Explorer.

> Note: This plugin requires administrator privileges because it integrates with the Windows shell.

---

## Pangolin Packer Plugin

Works like a secure vault system.

It can package encrypted files into a single standalone EXE file.

Packed files:

- Remain encrypted
- Require a password to open
- Can be previewed without extraction
- Do not require the target system to have Office, PDF readers or other applications installed

For example:

You can package Word, Excel or PDF files into a single protected EXE.  
When opened with the correct password, Pangolin can preview the content using Ghost View technology even on systems without Office installed.

---

# Use Cases

- Secure personal file storage
- Encrypted USB archives
- Secure media playback
- Preview documents without extraction
- Share protected standalone EXE vaults
- Open encrypted documents on systems without installed software

---

# Security Philosophy

Pangolin is designed to minimize situations where decrypted files are written openly to the disk.

Ghost View and Packer technologies aim to securely process sensitive content in memory whenever possible.

---

# Project Status

Pangolin is currently under active development.

Main components include:

- Pangolin Security core application
- Media Player Plugin
- Shell Plugin
- Packer Plugin
- Ghost View system
- Plugin management infrastructure

---

# Planned Features

- More Ghost View file format support
- Advanced vault packaging
- Extended Plugin SDK
- Improved queue & progress system
- Automatic plugin updater
- Advanced security logging

---

# Technologies

- C#
- .NET
- WinForms
- Plugin-based architecture
- FFmpeg
- SharpShell
- Flyleaf Media Engine

---

# Warning

Pangolin is a security-focused application.

If you forget your password, encrypted data may become unrecoverable.

---

# License

License information will be added later.
