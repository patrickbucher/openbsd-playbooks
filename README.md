# OpenBSD Playbooks

Setup my OpenBSD machine(s) (mostly) automatically.

## Prerequisites

- A full installation of a recent OpenBSD (tested with 7.8).
- A user user with `doas` permissions called `patrick` on a machine called `openbsd` with SSH access.
- Python 3 installed.
    - Edit the user in `ansible.cfg` and the machine in `inventory.ini`.

## Playbooks

- `basic.yaml`: basic packages, `doas` configuration
- `desktop.yaml`: set up a suckless Desktop environment (dwm, dmenu, slstatus, slock, etc.)
