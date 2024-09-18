# DVM Build Action

This leverages GitHub Actions to dynamically build the [DVM](https://github.com/DVMProject/dvmhost/) binaries for use by the Ansible roles in this organization.

The binaries are generated every night at 4:30 AM UTC and only if the main DVM project had commits since the last run.

---
## IMPORTANT
**This project is *not* affiliated to DVMProject in *any* way.**

What that means is:
- It is not actively developed, and not necessarily compatible with the latest version of `dvmhost` or any other DVMProject component
- It is **absolutely not** supported by DVMProject, any issue should be reported in GitHub issues and may, or likely may not, be fixed
- You definitely are **not** to go to the DVMProject maintainers to request support
- TL;dr - this is a project for fun, you're on your own.

---