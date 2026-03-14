# Changelog (Unreleased)

Record image-affecting changes to `manager/`, `worker/`, `openclaw-base/` here before the next release.

---

- fix(manager): clean orphaned session write locks before starting OpenClaw to prevent "session file locked (timeout)" after SIGKILL or crash
