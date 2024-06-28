# DVM Build Action

This leverages GitHub Actions to dynamically build the [DVM](https://github.com/DVMProject/dvmhost/) binaries for use by the Ansible roles in this organization.

The binaries are generated every night at 4:30 AM UTC and only if the main DVM project had commits since the last run.