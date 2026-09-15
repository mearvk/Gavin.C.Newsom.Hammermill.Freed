# Gavin.C.Newsom.Hammermill.Freed

A Look Over the Greatness of the Beer and Burger Legend out of California.

## Bitcoin Conjegeum

![](https://github.com/mearvk/Ubuntu.Determinant.Beta.Restricted/blob/main/images/Bitcoin_and_wallet_in_slots_2K_202609042306%20(1).jpeg)

bc1qs6v4q9zsw70t0umk3m0quhvf9dr6cdeskl28dh

US Democratic and US Policy.

---

## News

Active work across the connected repositories. This page links them together
and summarizes where each stands.

### Sleela — language, core, and Nordshrift

**[SLeeLa](https://github.com/mearvk/SLeeLa)** is a Java-like programming
language running on a Turing-complete, thread-friendly **C/C++ execution core**,
with **Nordshrift** — a `.sst` transpiler driver (spec NS-SST-0001) — on top to
drive a *triplet* of targets: **Java**, **Sleela**, and **C**.

Recent progress:

- **Nordshrift 2.0** semantic layer — an `.sst` sheet can declare explicit
  `subject:` blocks following the chain **Subject → Quantity → Unit →
  Assumption → Relation → Formula → Transformation → Result → ComparativeNorm →
  Evidence → Explanation → Validation**, so a computed value is never silently
  promoted to an observation.
- **Network- and Finance-aware component series** — first-class `network:` and
  `finance:` blocks with closed object sets, validated at build time and emitted
  into a per-target **component manifest** artifact.
- **Object catalog** — the machine-readable `SHEET.sheet` now carries **156
  objects across 18 role categories**, rooted at `System` (depth 3024), backing
  both Sleela's conducted methods and Nordshrift's object-compatibility list.
- **Sleelvac™ 1.4** compiler (supported `.sleela` syntax 1.0–1.1) with persistent
  runnable `.sleela` Core artifacts and `.xclass` (SecureJDK 28) input.
- **Wiki** — a full wiki (Home, Language Reference, Nordshrift Sheet Reference,
  Writing a Subject) is maintained in the repo under `wiki/`.

### Ubuntu — two editions

Two companion editions are under active development (**NCIQ** — National
Professional Software Repository as Ubuntu):

- **[Ubuntu.Determinant.Beta.Restricted](https://github.com/mearvk/Ubuntu.Determinant.Beta.Restricted)**
  — *NCIQ — National Professional Software Repository as Ubuntu.* The
  **SecureJDK / Graal Proffer** systems project: a common security and modeling
  vocabulary across SecureJDK 28, Graal, native C/C++, OS state, memory,
  process, geometry, time, and provenance. Its **Total** layer is a three-tier
  native C/C++ moderator (SecureJDK/Graal semantics on top, native moderation in
  the middle, kernel/OS evidence at the ground). This is where Sleela's
  Java-28 / SecureJDK memory integration work connects.

- **[Ubuntu.44D.Orange.Democratus](https://github.com/mearvk/Ubuntu.44D.Orange.Democratus)**
  — *NCIQ — Quiet Excellent.* The companion edition, carrying hardened,
  dated, and sourced statistical/economic reference data kept apart from
  framing.

### Admin Defenders — Windows and Linux

Two companion **administrative file-protection** projects apply the same
defensive engineering model — protect designated system files, directories,
executables, and libraries from unauthorized modification, copying, or
exposure — to the two platform families. Both share a **fail-closed SHA-256
verification gate** (verify before build, execution, and diagnostics), a
**protected-store** design that keeps content-addressed reference copies keyed
by SHA-256, and an explicit boundary that they never bypass the platform's own
security controls.

- **[Windows.Admin.Defender](https://github.com/mearvk/Windows.Admin.Defender)**
  — a Windows 10/11/12-era **file-system minifilter** driver (C, built with the
  WDK) plus a user-mode administrator utility (`driver-defender`). The minifilter
  denies direct directory-handle opens on protected roots — blocking directory
  enumeration, wholesale copy, delete, and rename — while leaving ordinary file
  reads working. It installs through the Windows Driver Store / PnPUtil and does
  not bypass Secure Boot, driver signing, Defender, Device Guard, or UAC. A
  GitHub Actions pipeline compiles both the driver (`WindowsAdminDefender.sys`)
  and the utility on a Windows runner via the WDK NuGet packages, gated by the
  SHA-256 verification step.

- **[Linux.Admin.Defender](https://github.com/mearvk/Linux.Admin.Defender)**
  — a distribution-aware Linux counterpart. A small, auditable **kernel module**
  (`linux_admin_defender_lock.ko`) resolves one administrator-selected path and
  sets the inode immutable flag, alongside Python tooling for a SQLite-backed
  protected store and a SHA-256 update manager. It does not disable Secure Boot,
  kernel lockdown, module-signature enforcement, SELinux, or AppArmor. A GitHub
  Actions pipeline runs the verification gate, builds the module against the
  runner's kernel headers, and validates the Python tools.

### How they connect

- **Sleela** provides the language, C/C++ core, and the Nordshrift `.sst`
  driver.
- The **Determinant** Ubuntu edition provides the SecureJDK 28 / Graal / native
  moderation substrate (Proffer / Total) that Sleela's SecureJDK memory and
  `.xclass` integration targets.
- The **Democratus** Ubuntu edition provides the hardened reference-data corpus.

---

## Repository contents

- [`MEARVK.md`](MEARVK.md) — project narrative.
- [`LEGAL.md`](LEGAL.md) — legal notes.
- [`LICENSE.md`](LICENSE.md) — license.
- `configuration/`, `doctines/`, `images/` — supporting material.

## Related repositories

| Repository | Description |
|---|---|
| [SLeeLa](https://github.com/mearvk/SLeeLa) | Sleela language, C/C++ core, and the Nordshrift `.sst` transpiler driver |
| [Ubuntu.Determinant.Beta.Restricted](https://github.com/mearvk/Ubuntu.Determinant.Beta.Restricted) | NCIQ — SecureJDK / Graal Proffer systems project (Total native moderator) |
| [Ubuntu.44D.Orange.Democratus](https://github.com/mearvk/Ubuntu.44D.Orange.Democratus) | NCIQ — Quiet Excellent; hardened reference-data edition |
| [Windows.Admin.Defender](https://github.com/mearvk/Windows.Admin.Defender) | Windows file-system minifilter driver + admin utility for administrative file protection |
| [Linux.Admin.Defender](https://github.com/mearvk/Linux.Admin.Defender) | Linux inode-immutable kernel module + Python protected-store/update tooling |
