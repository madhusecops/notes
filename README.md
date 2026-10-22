# DevSecOps: Zero to Hero — Notes

Class notes for my YouTube series **DevSecOps Zero to Hero**.

▶️ **Playlist:** https://www.youtube.com/playlist?list=PLL81LjMNEUlM

Each video has a matching notes file in this repo. The notes are the raw
whiteboard/terminal notes from the session — keywords, commands, and diagrams in
text form — so you can follow along while watching instead of pausing to type.

## Notes

| Day | Notes | Topics |
| --- | --- | --- |
| Day 1 | [day-1.txt](day-1.txt) | Course roadmap - everything covered in the series: Linux, Shell, Python, Git, Terraform, Ansible, Docker, Kubernetes, CI/CD, build tools, monitoring, security tools |
| Day 2 | [day-2.txt](day-2.txt) | What is DevOps, SDLC, Waterfall vs Agile vs Agile+DevOps, CI/CD, Shift Left, DevSecOps, SAST/DAST, SLA & priorities, AIOps |
| Day 3 | [day-3.txt](day-3.txt) | What is Linux, RAM/HDD/CPU/OS basics, Windows vs Linux, distributions, protocols & common ports, SSH into an EC2 instance, directory structure, user types, getting help (`--help`, `man`, `history`) |
| Day 4 | [day-4.txt](day-4.txt) | File & directory commands (`mkdir`, `cd`, `ls`, `touch`, `cp`, `mv`), absolute vs relative paths, key system directories, reading & writing files with `cat`, downloads with `wget`/`curl`, text processing with `grep`, pipes, `cut` and `awk`, editing in vim |
| Day 5 | [day-5.txt](day-5.txt) | User & group management (`useradd`, `usermod`, `userdel`, `groupadd`), sudo and `/etc/sudoers`, SSH config and `authorized_keys`, ownership with `chown`, file permissions and `chmod` (numeric and symbolic) |
| Day 6 | [day-6.txt](day-6.txt) | Compression with `zip` and `tar`, searching with `find`, offboarding a user safely, package managers per distro (`apt`/`dpkg`, `dnf`/`yum`/`rpm`), service management with `systemctl`, process management (`kill`), `netstat`/`ss` |

## How to use these notes

1. Watch the video for the day from the playlist.
2. Open that day's notes file alongside the video.
3. Run the commands yourself — the series is hands-on; reading alone won't build the muscle.

## Getting the notes

```bash
git clone https://github.com/madhusecops/notes.git
cd notes
```

New notes are pushed as each video goes live, so `git pull` before a session.

## Contributing

Spotted a typo, a broken command, or something that needs a clearer explanation?
Open an issue or send a pull request — corrections are welcome.

Questions about the content are best asked in the comments on the relevant video,
so other learners see the answer too.
