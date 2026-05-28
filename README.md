# DevTools

Personal Linux development toolkit for PHP, Laravel, and Nginx environments.

## Features

* PHP version switcher
* Composer wrapper
* Laravel permission fixer
* Automatic Nginx virtual host generator
* Nginx enable/disable helper
* Environment doctor checker
* Easy install/update/uninstall

---

# Included Commands

| Command         | Description                           |
| --------------- | ------------------------------------- |
| `phpx`          | Run PHP command with selected version |
| `phpuse`        | Switch active PHP version             |
| `phpadd`        | Add/install PHP version               |
| `composerx`     | Composer wrapper                      |
| `nginxx`        | Generate Nginx config automatically   |
| `nginx-enable`  | Enable nginx site                     |
| `nginx-disable` | Disable nginx site                    |
| `grantx`        | Fix Laravel permissions               |
| `doctor`        | Check environment status              |
| `update`        | Update DevTools                       |
| `uninstall`     | Remove DevTools                       |

---

# Installation

Clone repository:

```bash
git clone YOUR_GITHUB_REPO_URL
```

Enter directory:

```bash
cd devtools
```

Run installer:

```bash
./install
```

---

# Requirements

* Ubuntu / Debian based Linux
* Nginx
* PHP-FPM
* Git
* Composer

---

# Example Usage

Generate nginx config:

```bash
nginxx
```

Fix Laravel permissions:

```bash
grantx
```

Check environment:

```bash
doctor
```

Update toolkit:

```bash
update
```

---

# Notes

Some commands require sudo privileges.

For local SSL development:

* self-signed certificates are supported
* mkcert support planned in future updates

---

# License

MIT
