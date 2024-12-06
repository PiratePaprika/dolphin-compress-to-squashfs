## Dolphin service menu: Compress / backup directory to SquashFS

SquashFS can be easily mounted, so it's often more convenient than usual archives for backups and other purposes. No root required (but there is an option to use root).

When using [zstd](https://github.com/facebook/zstd) compression, you can choose compression level.

See also [SquashFS mounter / unmounter](https://github.com/shvchk/dolphin-squashfs-mount) (no root required, too).

**Supported languages:** Dutch, English, Russian  
<details><summary>Adding support for your language is very simple:</summary>

Just add `Name[xx]=…` translated entries for it in `.desktop` file and create a pull request :wink:  
To do so in GitHub web interface, you can edit file right there, then click `Propose changes` → `Create pull request`.
</details>

### Installation
Place `.desktop` files in `~/.local/share/kio/servicemenus`

### Screenshots
![Screenshot](screenshot.png)
